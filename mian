import mmh3,base64,requests

def main():
    hash = mmh3.hash(base64.b64encode(requests.get('https://www.baidu.com/favicon.ico').content))
    print(hash)
    pass

if __name__ == '__main__':
    main()
