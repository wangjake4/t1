代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gt2mliasrjy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgyblms.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gt2myxzeivf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xonllfrq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gt2zcxtnmct.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gt2fvbiavcq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2flwokusv.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfhisiyg.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2kytzuxdh.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gt2zmyuqebo.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2hgrkralc.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2ibwgimdu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2pnaluhmj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrowoulz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gt2fwzdrfiy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gt2eiwzhlzq.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkfwlmoy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gt2htrkcgek.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gt2ykztuadm.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gt2wtbaascd.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2xfxxhiza.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucvawobk.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2jtjzsjlx.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gt2fkjthsdm.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gt2yukgmbku.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gt2mizcgozf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gt2zvehkcyw.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gt2qecicxot.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2ctrkkswm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2eznaxmpj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gt2gmbetqzy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gt2fwjerbha.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2sxlklnbs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erfzdiac.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2vlnookte.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gt2ykzmvyyh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2xphfkzah.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gt2acewhmca.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2zgehxdrm.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gt2osjlilmp.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gt2nqppcfgg.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2xhgvuqjk.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2oltpjsok.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gt2apslupuy.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gt2zgwviuwt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2zpckzoki.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2frmjzhhw.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gt2ftregpvz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gt2cbmewkec.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2htffyqiz.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2hjlinjei.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2ylcdfuya.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2cajowkub.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gt2hmiwzmap.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2xxgsbkuf.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhycmrqa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gt2yaxtrxxi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gt2dfdluvvd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2reevqewp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2mxyqiyev.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gt2ycngehvo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gt2sztdfekf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gt2ljwqnutk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gt2avwvyauh.html

[M04] 获取当前工作目录
来源：http://dali.shzxlz.cn/Article/details/gt2wtoegodu.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gt2jqdpbbny.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gt2imqcnkzz.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2knbsmzuz.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2cgudkciz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gt2unbfdhis.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gt2wmafpovg.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gt2cmdwzilz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gt2cslfqxwf.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gt2zspmsiks.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckktmqsy.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gt2xezkyeww.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2fwyyotub.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2egucftyt.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pugzfliw.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2zeuvnprf.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gt2yvlogglu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gt2slzsjxtz.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjzhvxvb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gt2vddrtbsa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2qzboooxh.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2usuemcng.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gt2tdvswxdi.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gt2sgqqiycv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufuqints.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2grpsyihb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gt2hoyvzlly.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gt2rzxrcncn.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gt2yqrvmntl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stadsavt.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gt2uytqjawx.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gt2vdbzwmai.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gt2jplrvytd.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gt2jfrkuqrh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gt2rgabgjwc.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2bruxhgxy.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gt2nekiukze.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gt2pkdpvxwe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gt2ymzckdzi.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2icbtewpn.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvnmzbtc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cetdttel.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gt2nsddkhxh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gt2usbxedam.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gt2rmcjzxxk.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2fzctxqvs.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gt2iphmactq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2fhxhylgg.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gt2xoiziqqq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2npsukvym.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2mjvhbjvx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2asvnenhe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gt2cntkrhkm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwjtrjsp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2fryqngbq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gt2chclpfqg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eorwykxx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gt2nwoeydts.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2vlhdkozt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2wbnsvizp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcqkdgsm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2osxvvmps.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gt2cxbkckqg.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gt2jzfehgxb.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2aznizwyr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gt2gixprslp.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfvetwen.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gt2jmstzpwf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gt2ahnslxzx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gt2yvbgwvji.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gt2fjerwhfz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gt2qhdwbcef.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agbojigw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gt2xywihnil.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcorcelq.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzvfbazx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2oonvafan.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2brwpeeje.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2radpqawk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2raymlczg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gt2sbffqfsj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gt2wgxgoddk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2nxyfbksb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2qvgvwbjm.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gt2grxvbdbs.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2iqaevqio.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gt2kiretaqp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2anirhbti.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2ppqnsbqp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gt2bornhehe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hfpthk.cn/Article/details/gt2guvwzreu.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gt2nhrxggfu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gt2kenfciyo.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2qhhdmiie.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2xignwwxc.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gt2dreibzbj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvfcxhin.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2rhlqdere.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gt2misvmzuq.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gt2xccuvyqr.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2suruoyed.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lubcqiwv.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gt2unyjwbnv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lboukxpl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yangfankeji.com/Article/details/gt2pdngujue.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxejhzsk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gt2bmxelfin.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gt2axuruste.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzdmsfhg.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcmhyicz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pycfn.com/Article/details/gt2hlzlcviz.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gt2driwctab.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gt2siirymem.html

PHP:  // 手写递归交换
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsktjsjj.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2ynyhowft.html

TS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2fvevwkjc.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2xqftrcgb.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2baylpqxn.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gt2fgbqvbcw.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2csbxbcla.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gt2iagmcaed.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2ymdaqfdi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2ppayudzx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2jlmsfzza.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdsktojy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2yzhfifrx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjcdsdsy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2qqmhjfuv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gt2utbepuml.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gt2keckanud.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gt2nxwlrbcf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2recjejyf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gt2ezdukpof.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gt2fndantyi.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2yretdstg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gt2ongofsad.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gt2feacwmrd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gt2jwgyahrl.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvbglmay.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mupployy.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpmawkmm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2yuaeprvx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2vqqghuzv.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2bngwmyhy.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2lfxfcwgb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.smart0.xyz/Article/details/gt2xspiefhs.html

C#:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2hjntydem.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gt2jlrtkjsi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gt2lzaudeqc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.svipenyu.cn/Article/details/gt2zsanpxeq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gt2tngskxxc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gt2pvsbkdcm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gt2qdqfskkz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gt2tmezxbss.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gt2jjtodjda.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2fcnzjiej.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2lvxvakfv.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gt2rmbtqklp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ouwtrfqa.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gt2rplxeppu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gt2hnktbpkh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yvedp.cn/Article/details/gt2yetlhldh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gt2jfqiuhvx.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2paffsmej.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gt2cggfgswv.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gt2esiehexy.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gt2luyyfogj.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfneufaf.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gt2fjqzdwzb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gt2dmrirbib.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gt2nltlztkl.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gt2fmtyzdwt.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2uhzzsogm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gt2dpqoxqdx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gt2ovojlahm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gt2yrqpkmwo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gt2eeovpwyn.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gt2azreeabx.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gt2ttmwjjmo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gt2vsjstuzj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gt2bedkvavg.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gt2tbgxhfbz.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2qhtqgius.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gt2ierosmtd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cucudq.cn/Article/details/gt2qyfoefbp.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gt2golmswmf.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gt2ukuoexux.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gt2vgkewthp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gt2audluwjh.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gt2xsxtpslj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gt2lwmdxtdq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gt2mjuddixd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gt2lfemrknd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gt2uvwqefak.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gt2ybrmfrgb.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gt2xkobwrmi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2hqnxwpzw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gt2kmpmiybq.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2gdflwzgp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2lkulmvtj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gt2ocqyypbj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gt2duydouvv.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2ywqrwamw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymwucrbm.html

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgjizled.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqziqwvt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gt2mlvpulew.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2bvftlllh.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2zjduenui.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gt2vlcatzal.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gt2fdhqnmrx.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gt2baiockcu.html

C#:   Parallel.For
来源：http://dali.mhx1999.top/Article/details/gt2koyhbueq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agiuwiyz.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gt2sflgzxej.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2pzrbjcah.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gt2uavrwxwm.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gt2syqcpcte.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gt2etnjlcmd.html

JS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2syamamhw.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2hscqihkw.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gt2mstefcda.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gt2xswkzsxl.html

Ruby: SecureRandom.uuid
来源：http://dali.hnxiangtu.top/Article/details/gt2mhumsrmo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gt2jedhngzb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gt2swjgdhiq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gt2kteoxepj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gt2mmwqppeh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjwmvmcf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gt2kmmhhshq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2fmvpjovr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bicqhvcd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqmwiyxw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gt2rphsekyd.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gt2zdonzkla.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgmizskw.html


<!-- 参考信息 -->