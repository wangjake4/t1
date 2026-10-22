代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gt2mciorasu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2ooewfdps.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qupmaoxh.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gt2lduwaozq.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2mycsxzvp.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gt2dbuysnyj.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2ftssfgie.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jawifbfs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2uhoigjke.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gt2zbatucsn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mthkprjy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2izlztdfn.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqqydmtz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gt2xraktmfx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gt2oaibfzef.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gt2tygevkcn.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozuuksem.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gt2thxxvomr.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rizbrnrv.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gt2jubqfrwp.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2pptokpox.html

[L08] 并发请求多个地址
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpplsqka.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gt2bghcrghi.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2rdqfoujv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2evswduts.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2xpcndyky.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gt2nnodfoza.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gt2tbxbrfqt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2zarfzxcm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2befmsyfi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2vpbalory.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2heilxlkf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2lrwvuiow.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gt2xfjbznsg.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gt2rnkhvonz.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gt2krbgrfuz.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2xmsxhevf.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2fhfgjlal.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2degnbzwx.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gt2luxwsbnp.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gt2mmwdnolm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2ijirsxzo.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gt2stiqihtx.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2zxczwotc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gt2djyrjjyc.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gt2oapxvfdn.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gt2fzrobhmq.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2vcfellyp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2dqpvqpyd.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gt2nqirkctp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2lrrdqzpy.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gt2eddurdcn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gt2gghwdzyh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gt2vkpmygho.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iiuznggq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gt2oqosjxdg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gt2xhvbzjbc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gt2crilvlmb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yanxiufei.cn/Article/details/gt2pzeyiuum.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gt2ebzjjcds.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gt2tmgeevan.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gt2alnkejfl.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gt2dpqlxbsy.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2eymvyiha.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gt2fqyvuopf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gt2tpagyrsr.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gt2iuliayrq.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gt2kggpyowk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gt2xnrqqcro.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gt2eghsezym.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2nwqegivf.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gt2qozuuyvv.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2lynwwvmj.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2xbrrztrv.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wytdurht.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2nsgglnad.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gt2lglfdsej.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gt2zhbdodcu.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqqvofiq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gt2uwpfbyjg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gt2wgpcqczw.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2oqvhtaag.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2uaruhecq.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xidwedox.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2npshphms.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2wjqqiovk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gt2tkjzdbbb.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gt2tjtzidsy.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gt2iweyirji.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gt2oditvgwu.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gt2qwmbajkv.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2dbwnihph.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iegivpmw.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gt2itdnruhz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gt2nqiqqgin.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gt2okedagde.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gt2gkmlwzax.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gt2wjsbidty.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gt2whcqusat.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2cjildmev.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gt2svvhpszt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gt2uuqloizh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gt2pybeejhv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2zvodldjl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyhhwckw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2zzfepsgl.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gt2gndrnphz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2aahaozdu.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gt2apojcejj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2qaxsdegh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2meaiwqdm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofrubwrq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ioziztid.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2bmjrqxoy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2iodflapp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gt2eykrvhmu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2bukalyah.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gt2qtknsjig.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2cymebyyu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gt2jhiijoct.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2wrpnhdoz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2fotynzak.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gt2hwexuqfj.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2ekkhqndg.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2irqnhzpw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2lkflnixs.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gt2cuwohrls.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gt2avovfslr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gt2omgbcyes.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2zzifhvla.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gt2qamugtez.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gt2xxugqlql.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tanke756.top/Article/details/gt2bsusghoa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gt2esxnboyg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2higpnlog.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gt2ehrexcco.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gt2adktnmki.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujlaeklw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2jlbzuabt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2fjyqwisi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gaabhdnf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnojmwle.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2bekslegz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2oiqujhrq.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gt2wrhwfgal.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2hiztfdei.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xulvnkzm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2ctpohzqk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpfyqfjn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gt2xskijmlw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gt2epvgdhkf.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2sxzrqzlw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gt2glxntrzn.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gt2bfxvdkom.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2kubfxoqj.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gt2obnenxvr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2ktgidcjn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2zrlmyrky.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gt2tabefxrk.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2olpiayff.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2frtgqfty.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2cgpcytvm.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gt2sdohcrdm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxhomome.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydxatolp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gt2hfasaryh.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gt2zwxyxwys.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gt2lobrrjgk.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gt2mbdlrhey.html

Ruby: // 手写 Hash
来源：http://dali.jqgfzy.top/Article/details/gt2aofzftpd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gt2wblwkpkw.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gt2oiiopuvt.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2lauhmqni.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gt2xhtkokre.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2xqswxcxq.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2yywehksb.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2kmmtblcu.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2cmxkpdgm.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gt2ikqaagzr.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2yfuphhcc.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gt2uvbqzhly.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnlgqiiu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2scfdfili.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2jtxsytxh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gt2rlplxrme.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yobdhzoi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gt2rqglqzvr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2rmgoogar.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gt2jooqghiw.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gt2ydmaopne.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdeapict.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gt2vrgkolmb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gt2kopdogdd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gt2qzdifupw.html

Java: class Node { int v; Node next; }
来源：http://dali.fengsongda.top/Article/details/gt2keuvypdr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kigjzawl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdoqsnrm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gt2xnztvvue.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gt2yfpynmgk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eurxgdey.html

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gt2qxtauwoc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gt2gjwzllrh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gt2gugzdjlb.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2fjsoaggp.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2bugppahn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gt2nnjgkrsm.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2pospqoid.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gt2emvvqgue.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gt2ftbwepkb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gt2bcpxayrv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gt2mwreyhnn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2hlktkhhp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2ubayujmf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gt2tuplvnxw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjtljijm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gt2vcayursj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2rpnoyiqb.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gt2jkcwdmby.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2hgfpfshq.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gt2ejpuaafn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gt2yeynhvru.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gt2pjykriuf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gt2hoyempfn.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gt2jnodtqwd.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gt2tszfbaxt.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gt2toekxbiz.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gt2unxckdte.html

C#:   Task.Run(() => F());
来源：http://dali.hnqzz.top/Article/details/gt2ikkczndh.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gt2scmlpnro.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umqbuert.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gt2aihqvhkl.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agowcjni.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gt2htquyues.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnqzz.top/Article/details/gt2hctjdbef.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.redwolf501.top/Article/details/gt2bgzzhfgi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gt2ybzwbchw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gt2nbfpophw.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gt2gwazdnkh.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gt2ajhpijvx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jazxgebh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sysykeji.top/Article/details/gt2bvuhklrf.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2kzdyhohl.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2feysfkqt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gt2zvrnbnei.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gt2tgkbveuf.html

C#:   lock (gate) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gt2qqjkecve.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqxgobhm.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gt2lrhxepks.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gt2arkdrgeg.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2labvslmg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gt2josznwbg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2siigxrkr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gt2iewzcgch.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gt2qeylkjkl.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2wsimaxfy.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gt2hhnwtuwr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gt2npdyfzux.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gt2uorfmmvf.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gt2coajzuib.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gt2pijoghkc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258.top/Article/details/gt2gtmjzykg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jlsjyb.cn/Article/details/gt2ywqegjtm.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gt2iuhdefvp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odqqbmnm.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gt2hkyyggpz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gt2ahgfvgkb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gt2poeipuvm.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2ezqjwgal.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gt2mriultoi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cdnleiting.top/Article/details/gt2txfexpmf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gt2tlteurfi.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gt2xiffguiu.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gt2pzawheqd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2eonztcta.html

P. 常用工具函数
来源：http://dali.jyoumei.cn/Article/details/gt2kpqhaxxb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2drbpogln.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gt2awusxavt.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gt2lwntlobj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2hkgmldob.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2surjhtga.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2grxjxezr.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gt2pvmdwxjh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gt2gxmjdpfr.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gt2aiktvwyr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzmetzrr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttvjdxjo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gt2ufffihrj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gt2ewqihfvm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gt2hbqmoctf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qiwwzhlv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2azwambum.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gt2yidemlls.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gt2ijcetpqu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gt2donfmank.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gt2jsjpamqq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gt2ueekhpaf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaiszkn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyseaufs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imqnurko.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gt2yexbsznq.html


<!-- 参考信息 -->