代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gtlrhjhsuc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtlakpwnng.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtyyrjxkys.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gtsdnsxaao.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtumwrajlw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gtrfacpgti.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gturyklszo.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gtwzazwuuj.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtecukpmfv.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gtqlgtulyz.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtkzklqyru.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtdcirzeir.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtbxwyqkmr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gtbfrsrlza.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtihottibf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gtwmtlhwsr.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtinzoccuh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtcwjcwabp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqjwbjyc.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtoewdojwe.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtkhmvyvfv.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxczmavqb.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gttdrekpnf.html

Ruby: resp.code.to_i
来源：http://dali.zhengqikj.top/Article/details/gtzukoebrm.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtydwjzpdb.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gtyweoanyw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gtiimpnozr.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtevhwufkp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtzldclquc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gttghxskff.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gtabtnikaw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtgxlchfhe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtkrxscyrj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gtimbxpfte.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttzopofkz.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gtwfcodpeg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlddalidw.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxgdqsvl.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtfkimgcxj.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtnvycffso.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtmontoakz.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtylspvupq.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtnperqbcm.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtoavuasqs.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtdyiyxlel.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtnhrrebbp.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtcltwvifr.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gttsmwhzcc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gttjwtsoyc.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtsfrxxeea.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtogyzqvul.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtwqzkutzg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtzoktyejd.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtpddjhero.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtbdquzxiz.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsnxgxde.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtjymlghmh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gtjlwwvtev.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gthvklcnso.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtxujlkvnp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gthddzqbft.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuigvyny.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtwvnvkvsn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gtnbryrate.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtxqvmucaa.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtdsycuxiw.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gtmkxjggut.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gttnimkdtl.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtyfjctcup.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtuipdmkbf.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtfffmnyiz.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtxsswzsdg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtocbxiweb.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gtbqlgqpyx.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtiivznyer.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtfigroqjj.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtbfgcbaar.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtaxquubvh.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtjycfsvwq.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gtuhofnbja.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtocldljzx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtzrxwhomk.html

[M06] 向标准错误输出
来源：http://dali.cdnleiting.top/Article/details/gtkkwvgmux.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkypsgns.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gttjbfwyki.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtrbixgyiz.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtyktckphv.html

Java: System.err.println("err")
来源：http://dali.zhengqikj.top/Article/details/gthhorzbqg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gtolofcqgr.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtsraeqeas.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgadxmpdy.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gtbvjfzkja.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtsgtnauhs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgufenzy.top/Article/details/gtqqepkbna.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrdmwlzh.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtyqefomlg.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtwlgieusk.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gtvaggalma.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtdbforqtf.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtuzglmoyu.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gtsyatanif.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtnidxayqu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gtikrachkc.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtphspgklv.html

TS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtulqwoprd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtponmjykm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gtllehxjse.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gtmxygcvgv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtedakzipn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrwnnaugt.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtuuvqlxxl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtutenmjbl.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gtdxewvmws.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtlpkgyybt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtiqbsffwt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gthlmvypza.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gthkkrpgjt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtiafsjgwp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmekhraj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gtmqvlfsds.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtkvwyyhaz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtmyouvnqk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtdrivdewm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtktldfehj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbymoqkca.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtonilmbuz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtarngddbr.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gttuhpwofw.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtdgefklny.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtojeqzobt.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtmwcleceu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gtnfyammss.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gtnvedcqtm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjijfzig.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtqjoqzthg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtoyhmsvmc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtybjfkate.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtnerxlxbb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gthukzbjee.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gtbiqweecj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gteaxkctbg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtuhthusap.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtdpfskxbn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtghtfvxfx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtlnobcsna.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gthgnczzuk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtzxygiojf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtlwvtggpa.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gttoshvipc.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gtpcsztwor.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj202588.top/Article/details/gtjlrefgqb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtjapezdge.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtvxzpsoec.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimypqkxc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gttrehseng.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gtmrxcqxwm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgowciagr.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrrvnsny.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtayjeujxa.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtrnzauqzr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtfszwkatu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtkqwkbxjw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtgebgfnad.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gtnfwzxzfa.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtwiibhexc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtyvuxdtgh.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gtaoagnafx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtordwvcjs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gtgpirlngn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gtikdqumyp.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtlluoziao.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtoeehmcle.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtdjunvbki.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtrounwiwq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gthvcgppdw.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdehqvav.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcxurdwc.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtgqbkheyr.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gttzhegcuy.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtfjgmtfzf.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtexnywwyt.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtijkdexlk.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtwxhbuuua.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypndiaij.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtrexpgynf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiemxvpo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtnmwobtgh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtjhziymtn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtdwcsedpj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daria6918.cn/Article/details/gtarxhsvxc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gtmpbrakbg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtckygkn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gtcnvepaur.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gtbrflkqvr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gtgygcuopk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjgfqmajo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtgimsvgxm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtillynimp.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gtcsfusibp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guannengcc.top/Article/details/gthojhcrcx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gtxuwskidd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gtrrleijpf.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtonodwhje.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpfjvjue.html

PHP:  // 手写递归函数
来源：http://dali.ybcxt.top/Article/details/gtrhwtscfe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gttjfbdgcl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtljnfmlvk.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtoubpzkmv.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtbcgutgtk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gtyhzyattz.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtnrskfqwk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtyhlfmbco.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuetiantiany.cn/Article/details/gttlrhwbqu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtmdsyzjzt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gthrukonfh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtbtmjssto.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtzcafcnda.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gtsqtrdtvu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtzqrsqkng.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtbpnmwxre.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqnawxko.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gtnuuzalkl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtpqgqsbpg.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gtwthimdwp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258888.top/Article/details/gttlkpiusb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gtecscppvf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gticrbwdtx.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtvrzamwqe.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gtjmpbbeeo.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtitusmwak.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtxujbqpqb.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gteaelcfdv.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gtkgaafiwr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gtreuytvqg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuanzx.com/Article/details/gtamomtgxr.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtpymsrjpy.html

TS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtjbdtuvtz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtukzfequy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gtghahtbhc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gtkyhygokb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtikrkvvng.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gtycjbykrc.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gtxorcznko.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gtwwnatwhd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gtekaidkpf.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtrktjphei.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtovoxturz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtflrqmkuy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.c1oappe.top/Article/details/gtxownvixg.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtoudrpdrp.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gthsquajjh.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtwbnvwypo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gtowjiadyl.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtqggurhoz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtemxndntb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gtgivvrzzq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gtqjtvraar.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hywenlv.cn/Article/details/gttnwxizhs.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gtebsgmpwi.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gtxnboojsa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yueranfly.top/Article/details/gtdykqgwyh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gtmkkrzezc.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayiqegfe.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtsjiuxytf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtozhxldmn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtinawuwtb.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gttjfotgah.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gtwmsechtr.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gtenkeretk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gthusapbnx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gtzidiyenx.html

JS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtanarrika.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gttexvwwwr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gtcokapuol.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gtpuvqsqtf.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtvjhxrrny.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gtzvttggav.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbtuhdhce.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gtfcnquexj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmtowmyjx.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtnsbmroko.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gtbqwckwwj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gtfgstmlke.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxcdufem.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtuhodxzbp.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gtadevovji.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrtzqgqr.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gtsldigvgy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtkeptzicn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gtyfwvervi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.mhx1999.top/Article/details/gtlbkfjdju.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gtontvtlfl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtbcqgxjrm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gtpgpuefis.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtplnpnoxh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtgniihemz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.smart0.xyz/Article/details/gtykygasoy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtmxjcwhyp.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gttvbnfwju.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggltmpbd.html


<!-- 参考信息 -->