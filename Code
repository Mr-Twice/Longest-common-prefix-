class Solution(object):
    def longestCommonPrefix(self, strs):
        """
        :type strs: List[str]
        :rtype: str
        """
        prefix = strs[0]
        for i in strs:
            if len(i) < len(prefix):
                prefix = i

        for i in strs:
            while i[:len(prefix)] != prefix :
                prefix = prefix[:-1]
                if not prefix:
                    return ""
              
        return prefix 
                 
