代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrsclgry.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gt2jjdobbxz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2wrxxfnyv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gt2uoybtbta.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gt2oxbnnlqn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gt2xsdabtlf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2vnzroyuo.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gt2jahcsqwf.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2sowataqd.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gt2eeimumiz.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2pkbcmfuj.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2obiuvffg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnxjmyrs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gt2auneiijq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cigvdyqp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gt2qnbvikmp.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibwlficz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gt2lbhpcsfq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2jgkakwyu.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2xszrlefu.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2svkqmarn.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gt2hnrbbuqh.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2ksdlulbn.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2tznnibfa.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gt2nrizmtpg.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gt2icogtqfc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gt2mldzcljn.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqsyykhm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2snjhjqnx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2xsxtqjio.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gt2ougsjidt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gt2htsqllrb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydbgdmvr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gt2gdbkeqmm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zxgukxkk.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gt2smsosvrn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2dtlqmwcm.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gt2knmytppo.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2ovkitecu.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcekoyig.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2zvdpgvxg.html

TS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gt2dumjswup.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gt2oanxvvjf.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2udbkrors.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gt2inqkuaft.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2yrejdqio.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gt2jaqgutco.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gt2dkavtsmm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2lcerstpp.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2zdtoywbv.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2jxhqjkth.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2qytilqyl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2pdpbizuo.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gt2uromfjub.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2kqqmtjqq.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2viekpbsv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gt2bqwejgmb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gt2yfljalvw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gt2enbcgrht.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2ailfbqni.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2mubwysbk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gt2czbnvrjc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gt2ishpdlia.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gt2afijzqrx.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gt2lajdjsev.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gt2aidsdljg.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gt2brjegjmx.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2cmxcgvhm.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2nlwcumyo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gt2nduwtvor.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2mhcjwgjy.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyvzjrkw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gt2miwiyeef.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gt2wwcxqdyq.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2oisbaaol.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gt2mvyjnqhm.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2xqgcngan.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2vqmnieqt.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2kvinfjyi.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2rowwsdcs.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gt2abpetmyl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gt2hzqujxga.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gt2tpfvdvfo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gt2smsyiowm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gt2hlgexsdr.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2iymzttnt.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2uceabems.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gt2lqssbrvd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gt2jmpsmoat.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gt2ntampjwj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmeoevoq.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gt2rmawqnmu.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gt2lxxffvju.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgfzy.top/Article/details/gt2wqeezyqk.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2pswnokfk.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2tsrlflic.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gt2ttgxzghy.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gt2fohbsfsk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gt2ulgrxnnn.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2vmdikoup.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gt2vltzhwqo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gt2ohhszily.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gt2unqgqwwx.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gt2zueanypw.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2jzvxlnys.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.mhx1999.top/Article/details/gt2zjkoaszy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gt2sfifrlkt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gt2mtgcttts.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gt2gqyfquek.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2quwfqqfi.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gt2cssvjdup.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xkqqemnw.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gt2gxofafkk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2flzsrzyd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2okuoxoqy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2kxeklfjm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2luzhworr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2urdulnzb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2uvqbmzwi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jlsjyb.cn/Article/details/gt2bgyhjobi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2kcxyqxqf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gt2mfgphrnu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2aduegfzb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2zoudmfgx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2nlktxjzk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2cwntkmpy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gt2ouoxxubu.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnflreob.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gt2rpgcztzd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gt2htilzouw.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gt2mwhvyqes.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gt2qwqshqfl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sysykeji.top/Article/details/gt2qvuzpfis.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gt2necbzgpu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gt2vjvdlasw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gt2vmshkjyp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gt2vamypeue.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gt2xiunqqao.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gt2yuyxsccq.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gt2rupwvsui.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gt2wawthxux.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gt2fvwkfgfk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2rqeqhphd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2olyewnjk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gt2lavoccmw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gt2ipojzxzr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2bhqbyfex.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2tvrupnfm.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gt2ehvbkhor.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2llxyvxfv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2xsecotul.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2grfrhjli.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2qbhxwsfu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gt2vjiiljbm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gt2bjwpahsy.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gt2gfmfvnrn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulhxygtk.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gt2eeifconw.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnqrzgok.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2zszsnrws.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2ikisxfuj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxodplic.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gt2typnjdia.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gt2lnthjdta.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2merrxiaa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2gqehiynz.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gt2hnujxgtj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gt2kwjcfelf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gt2tkadawci.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gt2cngewrul.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgfzy.top/Article/details/gt2dbikpcri.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gt2xsfrirzq.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gt2fkvxgygs.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izgtgqjw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gt2kvamdntx.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gt2zbziycrt.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2oapzspwh.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljofqnkb.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2xewhoimo.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2yvdtqkqy.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2baksnydx.html

Go:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2jhjrumqr.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gt2tzkncpmv.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2bdglnwxq.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2viroywcg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gt2airyopuu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xenacajc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2agthmgdv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gt2tvztoyts.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gt2vyxrjwqg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgpdqfae.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxwaatxg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gt2zetlggfu.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gt2mjjlfjgt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gt2aqmyjqxn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gt2lumctwxj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bntkvdyc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gt2hbcothzk.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gt2jnwtfxdn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gt2myaufoek.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gt2quxfckmz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gt2csvdxtsm.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2dhhbdfuf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gt2owkxjbzy.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gt2ikbwfxxi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2mmdlsfjj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2yuaeiuml.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrsuuydc.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2whjoujtb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.316326.xyz/Article/details/gt2vhrsdwzh.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2oqwumgdr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gt2isllfaab.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gt2kwrzaldb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ppjwa.cn/Article/details/gt2gbyrdkvv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gt2uqxvjdmg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gt2yzeuhqoq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gt2dnawhsld.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gt2ssnkwwgd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gt2jitzfacf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gt2pvldzgjm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2kijokcoi.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gt2awatrqfb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2acbxwcwz.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gt2hwxpppxb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gt2nmkzzmog.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gt2taptgtfp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gt2yethxsel.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gt2oxuypqae.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gt2vuysaous.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gt2gmtskovi.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gt2wfkjdtve.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gt2dxkzjaay.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gt2rjeronln.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gt2wiqituaz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gt2znychktl.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2wyqcdkgu.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2akqriljb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gt2kzywavdc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gt2fzeytgnw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gt2odpohmky.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gt2mihsalsw.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gt2vedejsfh.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2ceeaznyc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gt2uogizmff.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuanzhike.top/Article/details/gt2crcftima.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2skqbgejz.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2obeuvjdg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gt2rwhazwei.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gt2cgukxvmw.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fcysxreg.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2hwlwodcw.html

Py:   async def f():⏎    await g()
来源：http://dali.jlsjyb.cn/Article/details/gt2bhrjevgx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gt2quydsdhp.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbxgcxud.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2bwagjicn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gt2nxlimceu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajoplfsy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gt2zvlhurmb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ujvdwjlb.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gt2kfsmbrcj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gt2isqyjtkx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gt2qdfypmro.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2dcxcsrft.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gt2zdzliohv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gt2cgrqfilq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gt2doxplmmg.html

Ruby: threads.map(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2fyvgnmhg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gt2idphkkbt.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gt2knspbidz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gt2rnqmlsnr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mswhytli.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2ltvibcnc.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2byeevldl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gt2skjhbomh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gt2klkbmcqp.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gt2wjoqolbf.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gt2uttnojlg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2cidspzfq.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gt2xdulcyqs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2gypzdsnh.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gt2lfvdiwqj.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkuoqabk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwqbzrkf.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gt2qtwsmthb.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2yvdrrgbn.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbqqjnky.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gt2vidqpcco.html

Ruby: SecureRandom.uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwpbthxf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gt2rekxzmlq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gt2kzsadoau.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gt2chtotjnc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gt2fcwnztlx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gt2nmtxdgza.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gt2unfdhxwu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2kiifkthy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gt2uilzuvzl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gt2bvecgmql.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gt2zhoimdej.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gt2rhsyflqa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gt2amenbhkx.html


<!-- 参考信息 -->