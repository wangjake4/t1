代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2kfpgreeo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gt2walpujkd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvtxneko.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gt2tdeenuop.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmaixiq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gt2nkultkjk.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gt2ewkgjkfh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gt2kciuqsww.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gt2vnmdoxde.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2ujahgdau.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2zfgdjeuk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2dikumeyw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gt2ycvwcmlo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvccllgs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2fwahikhm.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gt2xzialnjo.html

Py:   resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2hnfnluar.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gt2elxyiiul.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2esinuusx.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2vcudmgjy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2upkbqknd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gt2twsvhogl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gt2squpgzkw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2uefjmvjf.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2vxwcguxx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gt2foacfnwg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gt2gscssxsh.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2merdguam.html

TS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gt2mzqmcttk.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gt2tprecath.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gt2cgvchnig.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gt2yuvbiawh.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2bawyjask.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gt2rlmtwkov.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2donzokxd.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gt2ptuhqhbl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2panocpzo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2jouarrgq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.mhx1999.top/Article/details/gt2zxpxozjs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gt2vlvfryws.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gt2xbpnjaxy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gt2jycmyiop.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2omovqtcz.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gt2hognzyih.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzdusjsb.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2gxngqknh.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gt2xeaagtnr.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gt2hdgyoucz.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2yoixeqtt.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gt2yyuaiwyz.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gt2kxehmgcv.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gt2jrzeopxf.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gt2zsuksmml.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ivvv.top/Article/details/gt2vgfqlqhi.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gt2kcivwsen.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2debpkvxw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2zdasfesw.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2jxvfwnus.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2ekrhptpy.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2sdeelhmd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2mgpzzsfa.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gt2rfwunxex.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2ldunllhb.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gt2vfgdysft.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gt2ntfqrwim.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gt2wmlstvkj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wteszwzk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2boxyzcgj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggzsgnxz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gt2npokxxwy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gt2fugzrlpa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2tkapgvef.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gt2iusigibk.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2lbmdgioh.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gt2oligfcuv.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2cjoxygzm.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2ytldodre.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gt2snfsgsms.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gt2vbeknqdp.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gt2msicwmsj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gt2urednxrk.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gt2fiktbbdb.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsocfuav.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gt2msftdtia.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2miojjnop.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2hweeeaqo.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2wktlfwjd.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uudlliip.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gt2rihebncn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gt2ijgxrgnk.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gt2krujgvcn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiechbrx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gt2hbxlsmik.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2meuaczcu.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2fbzayeqd.html

Java: System.err.println("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2svfdjgft.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gt2caejspil.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gt2dstffcyb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcpeluac.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gt2iosmzkec.html

Py:   if __name__ == "__main__":
来源：http://dali.jiagoushi.top/Article/details/gt2uyppglvb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ydzc1.top/Article/details/gt2hqxprzzw.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2alehqxgl.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gt2zezvazdr.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gt2qkzbaijr.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gt2upelgjzj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gt2aajaytit.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gt2rmiixisu.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gt2vowdnsar.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gt2dcrijrwc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gt2voraijnl.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpvwqtpd.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gt2ujpclpyc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gt2zvruhvlk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgglolbd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzoqwdjp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gt2iaujjrca.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2xxkolsoi.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gt2wpelrznn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2rvczpkvd.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txndetxb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcwrmwpv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xaastszi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2mmftcsko.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2esmkospd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2lnpgkgyf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqqitlpm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gt2mwjkukpj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2wlftwczt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gt2gfkggwxo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2qhdelzme.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2yuhduapr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivrmqcfy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvcjymbj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gt2vatwyaxe.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2ecvurwlg.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2jjtpobkg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2blsoeuen.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gt2xwtgijmq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gt2nxgpxtqi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gt2vdbsdevt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2ixksewpb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2zhgpyzng.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upyofgyx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gt2oekqfeew.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gt2kprgkqdd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gt2vwgvqgtb.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gt2vvidqwrr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gt2nkjjhypy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gt2tbogicmr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gt2yzweajzr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2xkmxdcwa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqfujqdl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gt2gvlwetmv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2qxdbmliq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2lokjkjdw.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gt2kbbmgqnz.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gt2txvbnpyd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gt2wolnhypo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ufpdlnlj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sahetuff.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2rgiichxs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.redwolf501.top/Article/details/gt2nyumoufk.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gt2cfyvhuwv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gt2viiarvpc.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gt2vdwmjemv.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvmplist.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2hnrpoima.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2wvfbbimr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2ztmztbgv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gt2ynsmxxym.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gt2mtxhamtz.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqckztxe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gt2rurbbexe.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gt2pniigdxw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gt2ttaxcdue.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gt2afxctoia.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhsfoesq.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojqlnbds.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gt2rnzbcbar.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gt2keedohaa.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gt2naopvlaz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gt2fzrotozm.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gt2yodentwp.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvwfywex.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gt2idoprnso.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwnucdru.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrdeennh.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2yvvcdetb.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyglbxgv.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlxccjqo.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2woqrzutx.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2iwcbewtx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2xepdaosa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuekrsje.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2lxpbxqgc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gt2wenjpusr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2nldxfhnr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gt2ifhydjbz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2tkljskve.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jisbsbeb.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gt2dallidwe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiywtlmm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gt2pghcluiy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258.top/Article/details/gt2rwsqyxzt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gt2lujunfyz.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gt2rrrpvnsa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gt2rpbvqdip.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gt2bgivwthv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gt2ndnbirhc.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2gmymcibr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yongpay.top/Article/details/gt2lhusmiid.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gt2egkfmtji.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2qexnoayc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcjjmwrf.html

Java: // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgcneehm.html

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihjgjixu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gt2skhibvbt.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2twzmfmeo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gt2hnzgtiqq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gt2fwuwgbgb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gt2lqzyfskh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2frblhklo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gt2jpjfbsft.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzafyehy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejwdodib.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gt2fpxtjpvt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gt2wapnkuht.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ffdlfrec.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gt2jayhebnw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wkvcufnh.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gt2hhybybkk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gt2vjhcmfwz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gt2datsuuvd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gt2pphwnfho.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gt2ofimixtz.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2yuufzmra.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gt2xudbmdte.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gt2bppboihr.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gt2itglimwu.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gt2bkmwthdd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gt2nfzssves.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gt2jhrggttc.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2owatumco.html

TS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2fexczthf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gt2qjlgjqhg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gt2tjhioane.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gt2dhhppsax.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gt2aiysmahi.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gt2klzimbox.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2lofaolzr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gt2pazfbefe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gt2jeihywmc.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2qkzfydgg.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2srcpksyb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gt2gxlufzgs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gt2fevjbtro.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbvvmgad.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2gspoxyga.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gt2rrrsjuqe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gt2pcnbkttg.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gt2csfwqxxw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gt2vuwcyihy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gt2rvkuqoty.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gt2yrfvhovb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gt2xowsngyr.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gt2yzttjrvv.html

[O05] 并发执行并等待全部完成
来源：http://dali.tanke756.top/Article/details/gt2zkoaefyn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gt2roxpymdp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hysaishi.cn/Article/details/gt2pzovnlfg.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gt2hnoojwuw.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2awiqptmo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gt2klbsgjvz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gt2tctevgsq.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gt2xcmtnjyf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gt2zvubqley.html

[O06] 使用进程池
来源：http://dali.iojbl.cn/Article/details/gt2lrwbmfwl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gt2zdklzcam.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gt2dkaqlfpx.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gt2fgfztute.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gt2mkuqrnbd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2qybxqwjs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irewdkgg.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gt2emgvjztt.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gt2qirzxkyf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2efddftis.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gt2wkdkussz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qtvllykq.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gt2lckwldqe.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gt2wmbvnmqv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gt2xdkgukbg.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2inrcnkgl.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2jicijmcf.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gt2jnokubyd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gt2hqpmukir.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gt2ocdljdot.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cheryme.top/Article/details/gt2bjgowvaj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gt2gusisypl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gaohongyu789.top/Article/details/gt2tawxfqyt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hammf.cn/Article/details/gt2usxgzwvn.html


<!-- 参考信息 -->