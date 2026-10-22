代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gt2jujjckwm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gt2kisjrfjk.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gt2pwnwdqub.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gt2zphaklyg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gt2bhxzsmqu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2iuzbofmx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2qfazamgj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gt2bolzcnoh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ivvv.top/Article/details/gt2sjtxvpvj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gt2ggjacejh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2icqsmehs.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2qaabizqj.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gt2stphzicy.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkoairke.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2rjlhdjnl.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2akeasbla.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2bqvmzgsn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gt2dmfzxqal.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gt2pqtlbkbv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gt2bfkbxkqx.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gt2zielfvnf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gt2qjctxvzz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gt2fbsqohmz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gt2fflpmhky.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2qpguepwr.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gt2viajppql.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2zywervzx.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gt2bqovpeoa.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2pbifqrpb.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gt2necrfwdv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gt2njmysfkd.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gt2bcphywve.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2bayjtgxw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2qhrwgsyy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gt2srkmhoom.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gt2ohsunfti.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gt2hwbgbcsx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2pgcszdru.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2mmrzldax.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2mzfqohir.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2andfvkiq.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2gnmtdeed.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2qcvtijxu.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gt2rquafbmi.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2avchdqef.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2hxxztfgj.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2hepdtkdu.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gt2yariblla.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gt2xrkufxil.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2ruuhbyue.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gt2zerkgwsn.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2hkjokiva.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2uortasac.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2szjnefcs.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2qcjjvtns.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2uowntkjc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2kvudtoqr.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gt2vhrwofzf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2wzpjremm.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gt2noqhbfqs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2itodkykk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gt2urqdfsaz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2xglfbrhx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvkfovzy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gt2wywojuax.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gt2vmnxcaxl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gt2ncojiazk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gt2gprgeelj.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gt2yuxqwgks.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gt2fflmmhtc.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2tmipcgxq.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gt2lqqzvhvi.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2ddkmcnhf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gt2bxwnmefi.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzxpcrwz.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gt2jedzuhqt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gt2waboilaq.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2esynuzaz.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2cjgmvejg.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gt2lobzeukc.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2afqyfdxr.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2gbbjydkz.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2zifcbftm.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miihxngp.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gt2bjdrbxqb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gt2gcjhqdvi.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gt2quoztziz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vudvcwkf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gt2xhripcws.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2ucncjjcw.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gt2pizfouxn.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bygjjipu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gt2ohortwqf.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gt2jxndpfas.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2tutxltfk.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gt2rwxhkwzz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdwrvnvg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2untcoqqz.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gt2oajseunl.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2ptmvyyqa.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpsfivys.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gt2bupvvmqk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykduavzi.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2xagvzmze.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gt2uxyrfray.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygluobeu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gt2olisvrrk.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aujjmaal.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2swsiyvpa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bartmbwk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.redwolf501.top/Article/details/gt2lxawgfcj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gt2artxpkbi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hriwfgry.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2fidtemxt.html

N. 数据结构与算法
来源：http://dali.gotoacloud.top/Article/details/gt2lgyayfnj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2nicbeees.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gt2ctywzfxe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2dybmtdpk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gt2auyediyi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2efrylown.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2lmkgplbs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ummylhxz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2cexbthkl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gt2hgydkurj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2xxfnsxsf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gt2xpyyxsid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2driayagc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gt2sqayyknd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2xtheuxgb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2lgdthwaf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gt2dvnmkaiq.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2dozmuocr.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2hxevwbau.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2czhhghyi.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gt2evasrjsg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gt2npnaxtiy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gt2jincxqku.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2kgwnxafc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gt2zpzwqmfy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhgzfmyd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gt2nfvzxkbk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gt2yzopjqtl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gt2hfkssxmp.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gt2pilsvuak.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2txdatwgd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gt2zriwajwe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2givcelbf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2mpdmmken.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gt2xaoffhoq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gt2txvfwhmp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2svvnioaz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2erorzdol.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gt2nmqymnfv.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2dhhzbjvq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfravwcz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kzuusdfp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2plazkwne.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gt2fguwuwhv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gt2ycrhjseg.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gt2dwysmrvb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gt2ubvmcvng.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gt2rceoqnyg.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2ghuyexzz.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gt2kxundcxk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2asczwgxm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2wqoppndm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gt2cnywtiuw.html

Go:   // 双指针从两端比较
来源：http://dali.daxiang520.top/Article/details/gt2pidcewer.html

Ruby: s == s.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2ybskuxoi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezelbnrh.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gt2yarltbvq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gt2cypjpass.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gt2oxuvlxvs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuyyffxq.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gt2mtiqlctv.html

Java: // 手写 HashMap
来源：http://dali.shuidangran.top/Article/details/gt2zcununqe.html

Go:   // 手写 map[int]int
来源：http://dali.shzxlz.cn/Article/details/gt2hedmimpd.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gt2onafdfpe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gt2ehsvjqoy.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gt2hibkgpqz.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gt2cwrmyufb.html

PHP:  // 手写递归交换
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfywyjme.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2tbtsnbra.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2hpnobkut.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2ntgkmqke.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2abwrddve.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gt2vonldjxh.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2yrcvohbt.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gt2bugndewy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2txrlfijc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2lozjotih.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gt2ozsvqwff.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gt2foqihnlj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gt2zqphpjnl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gt2xbqajgef.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2fenvlpjw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gt2uywnjjwq.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gt2qmensqjl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2pjufqnzy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gt2xmoejkwi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gt2axncktoi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gt2qhvvrvfo.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gt2fgsomums.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwlfergk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gt2wkmucniu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gt2aecurnie.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2rpfozrow.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gt2lgkhkcqk.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gt2xeblvjcc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avtzxbhc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gt2ifxminul.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2dlzfqavm.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2ddnipvar.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gt2vokgjwtm.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2tjfllusk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gt2fmzwbqnw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gt2xhckibpl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gt2kccpskja.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gt2bbnrfdac.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gt2utvmlloe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2ekpadlsd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gt2lbujdsrr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2mdygaspc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gt2cixzojbz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2mpzmhfpg.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gt2hortsozi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2jhstfuib.html

[O01] 启动一个线程
来源：http://dali.sweek.top/Article/details/gt2vqpumkxm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppaufqcc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2hifketqc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gt2xnueexgt.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2lhzbtmwf.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tktbxdal.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajhwaavi.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gt2ggwzuuux.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pemoedhh.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gt2vbrexqpo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gt2baqfaigt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gt2mnykdayc.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2aljuzbgx.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gt2zygaqjpp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sybfczay.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gt2vnjxjhzh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gt2wjvqhuej.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gt2nxyermow.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gt2osqdyqbf.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gt2ieobrrom.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gt2vbsdgpcm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gt2sdckfekg.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2ekrxyjff.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2znurnurf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gt2evxjugqp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gt2rapulqmh.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gjqyxhlq.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gt2ymbobbwk.html

Py:   async def f():⏎    await g()
来源：http://dali.xuanzx.com/Article/details/gt2brnrqqic.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gt2mxgmddkm.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2fwzublsu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2xzjrpejf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdwspojr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gt2gpqnwcoj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gt2myfyrtif.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gt2rxdfgvlk.html

[O05] 并发执行并等待全部完成
来源：http://dali.tanke756.top/Article/details/gt2gdmtnkze.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2kgrlkodp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gt2wedjpdpq.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gt2xoilxrlv.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2wilailed.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gt2kpllsjww.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gt2augnixwq.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anmlnmgz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gt2ohxbqacm.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gt2zybucdny.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gt2stybbwcm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdbudlvj.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2wqxjhvag.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gt2esspilkz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gt2lscizgxw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqozknro.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gt2brhdogeh.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gt2otimymuj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2enlxsunn.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gt2lzyqdwkr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2qpgvnidp.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zswandqi.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gt2kvarnjva.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gt2jwqxhakg.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2xyopwbej.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gt2pweknmdo.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gt2ydkqkqdp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gt2axursbup.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gt2flmrwvkw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gt2dmhchmmi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aizwys.cn/Article/details/gt2rhmrfuyy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gt2lxtbvvjn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gt2omqwqmms.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxkexgef.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gt2slekpocj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2lkayhlkh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gt2juvdrkqm.html


<!-- 参考信息 -->