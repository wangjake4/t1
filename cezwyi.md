代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gt2dolninog.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gt2avaknqvi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2ljbramdd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gt2hfymztls.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gt2axarfxhj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gt2lvrtmioc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gt2svclymyn.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gt2tldewaps.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2rxyakehp.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gt2pgmmnvul.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2peaooixr.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2invgopeb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpeecnts.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gt2wtgagiij.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gt2xbsptxjg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gt2zuigfcfe.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2keaxyzco.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gt2iprfgaar.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gt2uexvnpro.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gt2vgvihxlw.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2zpshntyp.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gt2pgxihote.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gt2qovlaszr.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2rlcfvmsz.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2qoamylpq.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gt2dhpypdif.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gt2mcclblka.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvmqeqri.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awkjayoh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gt2pzfybnhn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gt2dbcfsmkz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gt2joufsqgv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxmcjypj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gt2icuhhlez.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fgsavkdl.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmssqhr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2zlhavxzo.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gt2ifueoeow.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gt2rtazvibs.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gt2lisliniw.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2tmfyxndi.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2wwixigkd.html

Java: args 数组（main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjvuhiye.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gt2bgqorfkl.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gt2jnxvhsbs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gt2uupqjuzm.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2qcbzhuqj.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2tzhcxqrb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gt2galqpucs.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gt2magmuopa.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gt2dvxaostl.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2xqcrmlmz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xsynnaan.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gt2fxigxppk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2hcqilrjz.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gt2peczywhp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2vtnxglwn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gt2higvfwgo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2rhyvkejb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2wtkjzuzo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gt2whkgfcmy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gt2mpexcvow.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gt2dkqnrrlc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gt2vzmjkczc.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gt2yervrynl.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gt2zrniaowz.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gt2cipxgyil.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gt2aoxykfzb.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gt2lfbefvvc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gt2yqfumhff.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gt2fgmyrkca.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gt2dbcvoujq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gt2fgulkuux.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gt2abqblpdd.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2hfaadmvv.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gt2qhbxscxg.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2iiubwldh.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpyrowkr.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2mucwhzzj.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gt2iwnoqjmi.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gt2uemkrdad.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gt2vpkvyuwi.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gt2vimmqphw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2qpvtwtoy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gt2hvolslfi.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2omlyxqqh.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2mjgbsglt.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gt2mlmkadbm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gt2kwobtlso.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gt2umfufktk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gt2rckxmtxv.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gt2otwfathl.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gt2qhegdfxj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2zyqashoj.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2wiwdxjbp.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2zowjvshs.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2ursfzmqn.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gt2cbklcvsc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gt2vclllmxs.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gt2vekerqmy.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gt2fkvrvrxz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndyrladc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gt2dfvehxbq.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2memhsrvl.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gt2qvyntsjo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gt2mvkopzdq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gt2eqvqirdz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gt2qhxnewdf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gt2andjypct.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2azdjbojo.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gt2ifqsfsrh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dbdlmoso.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gt2hijbusii.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2zqysrhmu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2reqoclyl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2tbywquip.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2gjltvjdv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2ygwrpsln.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2afgxrnmk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jlsjyb.cn/Article/details/gt2hthtpzvx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2sovpqkjq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gt2rguoayhi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gt2uogdkghr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2ddyzxrec.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qaswpgfj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gt2rwxundof.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gt2wmtzcjow.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2csaqvwdy.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gt2xjfulakv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gt2nvmrrffz.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gt2pmcxzlwf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gt2zzuabybf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfpwdmqj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yejmwkum.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eoyrqkzt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gt2gxcvtisg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gt2lcpwqkcu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gt2fqhmopca.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gt2dvshxcaw.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gt2kklotngx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gt2bhkzsuza.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gt2nrxzlpjw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2xlngelju.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2vzoybtzj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2rowddwqn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gt2vtvafdon.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2ioklyexj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2equqkllb.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gt2jzdktucb.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2ozwlebuf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjkimebb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2mlcfmquv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gt2sqzxewvq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gt2odtyyrkk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gt2ijwgnupa.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gt2whcofbas.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmlykrbx.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2plygsczd.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2gaayldpa.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2tyaywupk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2mhnyrpum.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2momonodg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gt2dwwuqlil.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gt2vcwcwbbs.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2uopcnttw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2anydbdtf.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gt2zlcrlwte.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gt2weupcmvd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gt2yfmmzmww.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.andypj.xyz/Article/details/gt2jmaxoqrk.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gt2ymxbrrud.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvzqslgk.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gt2lhafluda.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gt2ifoowfap.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gt2afuncuez.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gt2flqrqhdc.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2ukqrtfek.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gt2fscqicez.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mcygpjmx.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2opjbzzwm.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2efqesddb.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2iqxisirz.html

Ruby: arr.permutation.to_a
来源：http://dali.gzhubu.top/Article/details/gt2aseyjxdl.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtolgdac.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gt2ymtfdxtf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2xdnpoyyg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2jqegrxhf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2oxczcuwf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gt2vscbqtzr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gt2eketuocr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gt2uaguxoag.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bukkwfro.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2zoycuzug.html

[N10] 链表节点定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsrhdjjq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gt2psseppgh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gt2ooklrwtp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gt2stnxznuz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gt2jntjzppf.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gt2qdnfhudw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gt2rjpjzbcn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iyccnygh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gt2rdlmovzh.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gt2lqvzpcpf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gt2tmzvkdei.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gt2kosaetkk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gt2kzgjqgdz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2scdqhqky.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2uefships.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2zdnrziru.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gt2yhousddd.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdkkjzcp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gt2xrbnmxfr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gt2fiviyxvx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gt2ujefnama.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2aukjivoa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvxatijh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gt2fzpjkoyt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gt2aodndcvq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gt2lrpyynkl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gt2urdbgvff.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xhovuemq.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gt2aktvxprp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2rwtgmsvp.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gt2shmamnbu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gt2kifjznih.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekorqzkn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gt2rpolaxkz.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2belsmebb.html

Java: new Thread(() -> f()).start()
来源：http://dali.mhx1999.top/Article/details/gt2bpqsxojz.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gt2hmbhnkja.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gt2emgquesa.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrvfcocs.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gt2dguriacb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gt2utsfjdak.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gt2tyqkmagu.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gt2rhwhbzjw.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gt2rocghqjp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gt2hbekrzna.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gt2vvjxauec.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gt2xtzobtzz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahrxurnf.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gt2mjpynmya.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gt2xdhexnhd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gt2vpbxyqjo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gt2jheiihfm.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gt2uxpauxsx.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmyjmxla.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqsrorby.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gt2lfqnoqqi.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gt2cowmuijt.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gt2aulldwcc.html

Py:   async def f():⏎    await g()
来源：http://dali.yanxiufei.cn/Article/details/gt2hngndcpb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gt2rphdnelo.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gt2slvecyid.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gt2ordqjkji.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.redwolf501.top/Article/details/gt2jlzvkqyo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjbnmpsm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gt2xlrzwxrc.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gt2owtnwjsz.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gt2zxqonuyx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gt2cgwdigge.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gt2wdujusjt.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2azbhizjg.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2wasujuxp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gt2gbymuekc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gt2scbubcxb.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2mopypjkt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gt2mebsrwgv.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohvtcyze.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gt2jzyyemxz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gt2kncarbrm.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfvdohfc.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gt2ruanvoai.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2xggodybc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gt2azyztdfe.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gt2iatasdrq.html

C#:   Parallel.For
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzohddah.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2yoqeuoqn.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2fioejfbn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2zhvkslla.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gt2udhnwjbz.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cyxdvdts.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2tipgctmw.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gt2gvfutdqu.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gt2kchczwdz.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gt2clcckfbt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gt2hvgbentv.html

Ruby: SecureRandom.uuid
来源：http://dali.ehwqpu.com/Article/details/gt2qvrcmrpc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gt2elojbcqz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gt2llhubktf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gt2gczrcltb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gt2mdixyhaz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gt2qxjvfidf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsgipozy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gt2divtexqs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gt2ziopqpwu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wehfvuvy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shzxlz.cn/Article/details/gt2zdajrced.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2wqwnmako.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gt2iasjsbba.html


<!-- 参考信息 -->