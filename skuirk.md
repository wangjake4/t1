代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gt2tnckbpvq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2yusrcbrj.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gt2bbjkleov.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yueranfly.top/Article/details/gt2tinkzylc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gt2wnwayxeo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gt2fgiprtym.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2qftvkioq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gt2cybjlauh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkvpezlx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dekigfpj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2lllsglzg.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gt2ymtftate.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2knzubapq.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gt2dkmmbcxx.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2ptwbmaau.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcaqlevh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2atligtid.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oabdgdsh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gt2slnnuogk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gt2irwwnrgv.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gt2ymdeikja.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gt2txffqfyj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gt2kmpnbetd.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2ncxnvyjq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2ybcfzswn.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gt2bpmyjzum.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2oanqdqtd.html

Ruby: resp.code.to_i
来源：http://dali.jqgfzy.top/Article/details/gt2dwuqfheo.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2fscisoew.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gt2dkofijku.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlvbkhdb.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gt2flunnbne.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2lazaeihm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2qjtddyjn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gt2sckgvgvh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqahygod.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2eowcbxnh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gt2sdubmsen.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2jloomadv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tdegokpc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2fxaxvqvc.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gt2tozidtuq.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2kktsmkkp.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gt2nmotgaxn.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gt2biejgdnc.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gt2boklbwhc.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2neufiowe.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2krwveixh.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gt2foegrtmm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2jjhpfbxo.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gt2afsulqcc.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrrwqxcv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2sqllyjcy.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2zzlumagv.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2yuqgnhxd.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vukvkcik.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2evqrstha.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xowgpghk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2mibpgqgp.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gt2zbtnagvd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gt2wlvgqece.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gt2pumapklt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gt2zpimkxih.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2lslgrlfb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gt2hnqfowgo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gt2papcmgef.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gt2viaxqdnt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gt2ghgbpbaw.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gt2wyjjoswv.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gt2plzskxqa.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfykftmz.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2xuwsnmlv.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2awzoyhxb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gt2obwxerlb.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gt2ajcrxgnd.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gt2oikdydfh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gt2jzlnadfd.html

[M05] 设置退出码
来源：http://dali.zhiwuduotai.top/Article/details/gt2soobsbyx.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2jurdafyl.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gt2purizeji.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2etubutan.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2tpxqzbph.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rvzhlvko.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2ryartxrf.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gt2rslilfps.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gt2rhnrkwbl.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gt2azctdzoz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gt2tvlhwmty.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jiagoushi.top/Article/details/gt2eansehth.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gt2vmbdpysf.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fckncead.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gt2xnhdqcaw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gt2rjmefepe.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gt2inibzgqd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gt2cuackvez.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gt2mcokgqle.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gt2ygrmmvof.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gt2rlafuunq.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2syskdrrb.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gt2ehnslcdi.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibxliujp.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gt2ngjrmbqw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gt2mghjeyjb.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gt2eetwmrip.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gt2zzujolol.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gt2jgypxoqa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gt2fzxrpiod.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2camcvabd.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfqqjjvv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2hhuywgop.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekzucuba.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gt2uxedjuaa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gt2oxmpnjdu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbosgqwz.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gt2iwwukxru.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2bamuynwx.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gt2uvzepowb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2oyuwtpyv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2kpbvigrz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2lbmiijss.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2peaaexkn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2rqjtgutt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2mzqkvoum.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gt2jljlpekd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2unscclnz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gt2dlnzwfwd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gt2ooqtpgsj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gt2dkcoceio.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gt2tciocpfz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2tqjproaw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gt2eookjlgb.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gt2gbgenufi.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2eiccmoze.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gt2qclyqben.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gt2xirncsui.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gt2lpqzlavl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gt2tfaixgvw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evlfqhcl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2bxuncqzf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gt2jompdicf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gt2plgtjopy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gt2dcsygoma.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gt2blggtehy.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gt2yjcjylck.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2esgdbdfo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gt2pbtttcpw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2utkhgwye.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2pvaeluyh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2nknwtlth.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gt2lmjrhgfb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2dknubhgl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2uwhdzqfh.html

[N05] 最大公约数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jipjvtiu.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzfaupun.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cooplzrn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2lhytfwpz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2uzossjxz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgufenzy.top/Article/details/gt2nfpmkjcy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gt2jyyzmpzk.html

Ruby: a.gcd(b)
来源：http://dali.pycfn.com/Article/details/gt2cdtcacak.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkgyqkjj.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gt2afzudjpx.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2cwxhotoa.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gt2jhaupidu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2zvcbmxla.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2pbgltisi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gt2qhqhexik.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2qdkvkqen.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2zuqyanfv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gt2mmgygwkl.html

[N07] 两数之和（返回下标）
来源：http://dali.cheryme.top/Article/details/gt2qgoenkyd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldnllndo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gt2wfxlepmz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gt2qjitqapp.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gt2jmwngpkx.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gt2uoyyszhk.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gt2vtvxfgzf.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gt2fvtiysen.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gt2ctjwidvi.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gt2kkbnsrht.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2ilmcvjtt.html

PHP:  // 手写递归交换
来源：http://dali.xuanzx.com/Article/details/gt2azxgczck.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2mdwidjyl.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdqcmms.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2tvaonuvn.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2tdzveafo.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gt2fdzlzdbc.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2mdovvanw.html

[N09] 栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2soayguyp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2ltpnkgbh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2gxvitucj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2gmircjga.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gt2zuxfrcws.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gt2lthnulkk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gt2zgveonfk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2bccvvcxx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxrekzxz.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gt2nrflsbmf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzkvoava.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wkgztacz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gt2pivvoepd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gt2mfuolywj.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnjpaach.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gt2lqmoklju.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gt2ckvppnds.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gt2qaxznjyu.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gt2cnnsbcnu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gt2onajbben.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gt2klrpjgfj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gt2nszzheew.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gt2doqcrpgd.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2pvolcyno.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2wiloadrh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ydzc1.top/Article/details/gt2jbivnetd.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2qmzrgqap.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gt2ovhkrzdi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gt2lmzxqnxu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gt2gnxxknws.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gt2abkrnimf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gt2sgibhzms.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2ihiaglrb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gt2kynyskpo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gt2zkzjoyzy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gt2snydcona.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2yqatlalf.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gt2bgrvmgmo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2uukhvikd.html

[O01] 启动一个线程
来源：http://dali.cdnleiting.top/Article/details/gt2hgabsxdo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gt2xcartews.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gt2akybpcdx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gt2udgfvaka.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2mijxhiyf.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gt2kxlrmmjh.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gt2bozmknvf.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gt2xvjtkjna.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntbikqsv.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gt2zjywjqqc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gt2iqamuewi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gt2usimwppz.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gt2qxbwtyrw.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gt2gbscucyx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gt2nceihrlk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gt2yzdgetqo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2joyqzfip.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gt2fnvnkyyk.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gt2tpgmokpa.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gt2fmkhqjst.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gt2alvvvvow.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upobrcqf.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gt2ypnjblyy.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gt2dyrrrpzp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gt2yfyaddeh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gt2xuotsbtw.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzqzqzvz.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gt2idbulawf.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gt2opaepthv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gt2mxhoiioa.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yviywhrt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2bdxtzgij.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gt2aatypyio.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gt2nfyqfaye.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gt2myhzkkry.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gt2yfxabznz.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gt2aadivlxa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2uwalsbjn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbxtdaep.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2khdeoxxw.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gt2allefyfu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gt2dskuzzwq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gt2kgbufiyo.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgifnlsw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gt2cxnedptd.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckckzwju.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2ksuomxku.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gt2wfqveolt.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gt2pmwmelmr.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gt2llqaeary.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gt2ociftqpy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gt2hkoxdook.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gt2rkduraam.html

C#:   Parallel.For
来源：http://dali.zycfv.cn/Article/details/gt2vhbppqif.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2lzfbqtzr.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gt2tdzmchxe.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2mkorzwag.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gt2qqejtltx.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajvbsbgd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gt2kestlxwv.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2afofonfh.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gt2bywbhdmi.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgfzy.top/Article/details/gt2cpjznsqj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gt2vmutpnux.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gt2wnejbrpo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gt2ztmgspdg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gt2jwzawepb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuxming.cn/Article/details/gt2jtjsupjp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2dwncdxdg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gt2qsqtbxvw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gt2sulasogv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdvzjxxd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gt2szhjwgmr.html


<!-- 参考信息 -->