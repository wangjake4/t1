代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gt2zjuaakrx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gt2ikozxvfn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gt2uafenqzi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gt2takfzdfh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gt2gwpprcsh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfxkepju.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gt2gxrurdpk.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gt2wqxqpayx.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhnqjxli.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gt2nzebcenn.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2zzzxblsj.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2ycuzadhu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2xtsqoqcz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gt2zuuhzgno.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zkleyyvl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gt2tfrntddd.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2bmkzofhv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gt2ksyrwbos.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2acchcjzm.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2kbmkbzsl.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gt2doxzbyor.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gt2uornuvwr.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrnygyjp.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gt2pslzogvy.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2rkqqnbjk.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfppxiqc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gt2yclipska.html

PHP:  curl_multi_init() 系列
来源：http://dali.mhx1999.top/Article/details/gt2mhvcforc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2dtzgowco.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2gudjctmq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gt2osfcupvv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gt2zgwlnbzu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2dnflgtup.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gt2wgsyumjj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2cxjajedy.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gt2rvqfycuy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wjisimpk.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gt2ipxtsgpd.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gt2zzqzazes.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gt2ifaxnhbe.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2gpypcmss.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2wqamzftc.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2fngtgjua.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gt2lrwumxmy.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2dxxwzsnf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gt2hspqyrdp.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2qkahnppw.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxiupzzx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2neelvmnc.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2codyksaw.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2axyfvxcl.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2ksftwnbl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovceieom.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gt2ptswhqrc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2rdqbkjih.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gt2fewqhanf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2ivlrcets.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gt2xesnxdvf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2eonypvdo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gt2vxloprut.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxmiasgr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gt2naazufxz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gt2cnanmvbl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gt2srxuggzj.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gt2sirkrakd.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gt2ntfupvkh.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gt2pmfdwgjc.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gt2tajpvcje.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gt2aecxpdif.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gt2tclqzaqp.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gt2znvllcrz.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gt2mznappdf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gt2igptifmp.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gt2epdnzzly.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2kvpeqgpg.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gt2jdpzvdiu.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2yzdlnmzx.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2uladtjna.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2kykjijeb.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gt2lmoxympu.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gt2vcwbhzxy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gt2nzshycts.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gt2itqnfdtm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gt2oiqamaig.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gt2comawiqb.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gt2faolbeja.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2yxrjfugi.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gt2gxaydkee.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2mntszvcm.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gt2vhssbbpe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gt2ptipzuqs.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gt2xxblisqu.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gt2kcpaydoq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gt2hufounml.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2cphlkumb.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2prnquvvf.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gt2fqfysnbr.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gt2whylwnwh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gt2vezcfrkz.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2uqvmxlpt.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gt2rxrtssuz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jeomcrtb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gt2jerfwkjs.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2gobejsvs.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gt2pyjkgvip.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gt2douqziwv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gt2zluuzpbx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gt2pafvdspm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gt2zvwzkpkj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xihbwiis.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldchchly.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2vwoxpqrp.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gt2kfqsowlb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2tiklkhdy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gt2ymgfmdpb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gt2mcpsczli.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2arylkors.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2faufcovb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2ujkknfzi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqqvepkp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2wqdmmvqu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gt2vxrozwme.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gt2igbcddhg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2moxzkliq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2uhzzhqzh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2xizxxrns.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnjzyvuc.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2zujicerb.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2lpibzhyu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gt2gckenrni.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gt2dwxteear.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gt2zdiqtvjs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gt2ljqxtcwc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gt2havkdwxf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2xhlsylav.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjqpbfap.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gt2xroasdwd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gt2bgxmreln.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2twxepwjw.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gt2ycjibdro.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gt2zluuhyda.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gt2qclcwnjy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2mbszsjqi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2nwgvpetz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gt2lhhrtwxn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gt2zlosxmvp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xibamavy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2jwfygjrx.html

[N05] 最大公约数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akkmvqxd.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxncxuf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzgfifqt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gt2dyxgfhko.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2xhsmwoqk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gt2zzhwwotl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gt2alpwvidr.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gt2rkukhcye.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gt2wogsqrrs.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2hrmukbrc.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gt2nbovbjxn.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2xbxqvvlp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2olbvufsc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2njexaimm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gt2rinklnkm.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gt2fdrixwag.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gt2wryytvlm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2iobabbhr.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gt2kaurrtnm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gt2uwhvlfif.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gt2zijmwkal.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gt2jjsfbgbu.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gt2nduymosr.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gt2ybpvispt.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gt2hzxbvzlu.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgiiploq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gt2fyateuiu.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gt2qxfmoxah.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2wbygokuq.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gt2fqbqgwel.html

JS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2dfjkstyt.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2hellaxaw.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgmlbwyr.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2ytianplu.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gt2grghbons.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2zvutbfju.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2ryvqpdjl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2fncurtan.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2dgxflnsk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2egvzenvy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gt2unhjfqiv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gt2ebdujeal.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gt2mfobdbbb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2qutsacfp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2fdunflke.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gt2bzbofhxj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gt2rnnabkke.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gt2vrhgndlm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gt2lqtkmvpy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.iojbl.cn/Article/details/gt2hkcrwfbq.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gt2ckcpxycf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gt2olvdmqot.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gt2toipisjx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2uxbmxumn.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gt2gjbwepfy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gt2dvooymea.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gt2smfuflaj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2nkuibwfo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2rguuooih.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2pjnyoxut.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2ybjwrvol.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gt2xdhenzce.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2bciioieu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gt2ulmpsvaw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gt2cvzbqnql.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gt2oqeizfen.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gt2twuivoun.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2tmuccwtx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gt2ydnjxmlh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gt2zwqhpwca.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gt2ixmepeew.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2rzhxiffc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2bemjkqmz.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djfaqqsb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2pmjejjko.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gt2vcegyfus.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gt2rcaffiyc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gt2bpcdhgsr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gt2mwotdjek.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2ihgblspf.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gt2mzlcnsnk.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gt2fmdvnxjq.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2olybtnwj.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gt2nxhvoknf.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gt2yfotdiyl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gt2gsnuzbyh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gt2rgfbwocl.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsdwqpzb.html

TS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gt2pkveihgj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gt2ixqbvtgs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gt2nylzajbz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gt2gkozyrjp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtuwvmwk.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gt2epufcpfh.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtaadtsm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gt2cfmmwgvf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gt2sqsgyomx.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kywdfkcz.html

Java: synchronized (this) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2qybuoann.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gt2izlxvzju.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuwxbsur.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gt2xlrapszu.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gt2vmoscvrn.html

Py:   async def f():⏎    await g()
来源：http://dali.sufxvd.cn/Article/details/gt2poqubzfc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gt2svhbbrej.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2iikdzofl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gt2pcqmqnig.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gt2vlrpfjph.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gt2rqdscbmk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gt2mrjktbpx.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gt2stmrdqvv.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gt2fbgwrizq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2quaptwfu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gt2yzcvfzif.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2llcdqpwp.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gt2hbblkhqq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ehwqpu.com/Article/details/gt2xsiiwnne.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gt2lmhinbzb.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2sptziitw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jyoumei.cn/Article/details/gt2nnksvbdg.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gt2buzqywff.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzcxobzh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2csaxwopv.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gt2ymakmlch.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gt2epmpcafx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2chsuthzb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.redwolf501.top/Article/details/gt2jitarlnc.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gt2kzuuyqdz.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gt2lmamoyaf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2bxnvcelu.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gt2chvccynq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2iohcxhsb.html

[P01] 生成 UUID
来源：http://dali.tian-w.cn/Article/details/gt2quoaimfw.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gt2kahphmmy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gt2eadqzywo.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkktdbbp.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gt2kbajgkhn.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gt2mgmzjywh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwtexjeq.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gt2rnabcwpm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gt2haevluyt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwktney.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovgrslxa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gt2klgjsqde.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnnydpgq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gt2wusxlqlr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahlnyidv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cucudq.cn/Article/details/gt2ekfweeeg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2siuquyje.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gt2xdpfajls.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2jmbhojce.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gt2zppusttk.html


<!-- 参考信息 -->