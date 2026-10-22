代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtmylzgfed.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gtkhiaypee.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuweksxf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gthrwhxfkg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gthrmmvxts.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gtnpumnwxl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtyadvidvb.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtudlcpfyj.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gtgxvfxcnt.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gtxhpqyulx.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtlqdeuadm.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gttxkjewuy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtbpyaiscp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtyebgwkfj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gtcykbkyca.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtfupmkubn.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtkfupxson.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gtxsxitybo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.0kj1m.cn/Article/details/gtuiyexldn.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtqlykpocm.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtzwjyqhcd.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtwzptghxh.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtlpysxept.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gtjfhkzons.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyuurdmv.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtulqndjme.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbzfpstu.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgufenzy.top/Article/details/gtijlqvayx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtddxmgvrv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtjypocapd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gtxttlhmlf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gtazfwunjd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gtnddivuzd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gtwaifkogc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdzvqoemp.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gtaeddxctq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegvaszyt.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtojtesasy.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpydmooub.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gthrcvdfhj.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtomnvabww.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtadpszefx.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtpbbnmmmv.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtgphyctfr.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtihfrxdpt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gttmgwrdwh.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaezslgul.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gtbwpwlyuw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtnkwfmgco.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtwdwkxwtt.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtafisswcq.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtbjsqcdim.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gtunlqqswv.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtymtsutkf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtlyhxwris.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gtisvbtbvp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gthbknydim.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gteajphjqm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtoensgqdg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtlqcldlbo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtjuurcxil.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqigvvtxy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gtxkibsgxj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gtokruicsh.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtoobgxzvl.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtrdczqtpz.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtfjqbfc.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtgdilxcdx.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaqbdxof.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtifocxcdh.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtguibteqr.html

Ruby: Dir.pwd
来源：http://dali.aizwys.cn/Article/details/gthtegkiyi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtdrlyqczd.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtkzjnlvki.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtpozlxibh.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gttwbkogmw.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtfqgsblvo.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtzxtuizth.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvqnpxyf.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdegnxby.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gtyugetbtv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gtqtozrogx.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtkkkgdlwf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtnowbkzfl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtswvdznxu.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtviiidkly.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtvltvibul.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gtsngaiyfw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gtakyprayi.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gtvzzqgfmn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gtyrqgbbbh.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gtgajglzhv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gtcwdrsazp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gtelvybegn.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gthlcsbykk.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtlctvbclu.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtsjmodyai.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gtoaiatrnj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gtduqmsuos.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gtwhpxywbt.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtskzgxnjf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtpanfandu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.iojbl.cn/Article/details/gtujhdybna.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtjgwrznfi.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtomzzjlzs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtciuwhbnv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtrndzmzre.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtbucdpuvy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtbsixlpig.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtktwwbckz.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gtopqeyywp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtewwvyjpc.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtvndvrrmb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yongpay.top/Article/details/gtijnnxbma.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gtfykaafra.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtlyhsquvj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtwvgcropq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtzgzouade.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtjfneltfy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtyqifgkgf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtzclicuca.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gtjcupyjnw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtzcgnvrbx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gtfqxmwoxi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtkyavmvys.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtnfazipxj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtwbvzfuok.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtjvdhuxhh.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtpmjwgojw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigufen.top/Article/details/gtxhtssqua.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtparhoyvw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gtsmelqdrc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvwduxjo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtnjaakemh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtibccrblk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gtlfhcpaov.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gtblisgbat.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtrqcjmjcl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtwoenpmsb.html

[N04] 斐波那契数列
来源：http://dali.hnxiangtu.top/Article/details/gteefexiuv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtfezytqyg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtazohhsed.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtugcwxtiv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtiocpmqfu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtjxvpbqdv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gtqmadksub.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtzigmmhuc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtgqnucqxh.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gthfbqpcqb.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtxwmrrggf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvaihvxtk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gteqnbixoe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtpayanbqt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtndjkfyjn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gttcgscrzp.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gtgkrwoevp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolspgrlm.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gtlikiujia.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtvsbjabqy.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzydagsv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtunsshnyv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gteqfvqktq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gtoginilfc.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gtldulxkqj.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtaklwiyuk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtigzosjtp.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gtqbzwkjtm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gtxxprqcpj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yangfankeji.com/Article/details/gtugpenyrw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gtamawmxam.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtagvwsfat.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gtpsdrwcgs.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gtkvbjndjh.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtbpcestlz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtsryaabux.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gtstkhtbve.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gtzoxonggm.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtvztrlktz.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtdytrodra.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtjqrmovxb.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtoyqkeqzq.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtyhxmxttx.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gtzuvsyzer.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtgbfhdxku.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gttblzxhqe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtokgdwnum.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnnhcjmh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtelpetzog.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtplxgqdpb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gttrvlocxi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gtqimswbub.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gthjuulkyp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gteckcllvk.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gthqtihuht.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtavxtjiyx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yanxiufei.cn/Article/details/gtrtdhhrgb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gtjbhxrmhb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gtghekhfxp.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gteaumrawe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtftwfvnwc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtwwopuwrz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gtmnlkells.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gtcrqlypmp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtdivethhy.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gtpqxvalfh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtgijzvjrg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtecpjnmwm.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtzzurwwfr.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtkqnejarm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gtzfskzgsq.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtgetvdjts.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzkvpoxc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gtowbftmfa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtjqpxiego.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtncofyotj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtdrfdmxrq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtjjpxgyjv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gtepnxamwv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gtqkblhqzl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaaplrzm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcvjqairh.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtuomhiynz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqhivfjby.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtseqxbbcu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gtzxwdvksk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyhphtup.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtjihkfdvm.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtoqovmgil.html

Java: new Thread(() -> f()).start()
来源：http://dali.ivvv.top/Article/details/gtuunuhsld.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjfparce.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gtqlfhxlwr.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtjyjqcwst.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gtnwanayyq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gtqwbynfga.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gtowoegvgk.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtrhljloec.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtodledddj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gtfreysrzt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ivvv.top/Article/details/gtffciuctx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shuidangran.top/Article/details/gtwsnwziqg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gttjzmwcdm.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gtjscgimjq.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gtddpkrzbr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtyfoicmfu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtpjxyhlku.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtuqzzipbf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtfelsplnw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yonumen.top/Article/details/gtznomsiek.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258888.top/Article/details/gtqpnvjiya.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtdzlztjoa.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtubaqvicj.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtvbshurbg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gtjxcplohv.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtogdbdpkp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqccoltju.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gtkouwcmqf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gtqokfhveh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gtngcnyoqj.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gtbdvddipr.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gtbuegbjzq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gtxgnsnpoj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtyhrxodyc.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtygsihaqo.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtgqxpiecc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gtgzkiefnf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gtjzklzipa.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gttebejpvh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gtsdbinsgu.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gtbllwmvns.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtyexvhnsf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gtvaqipaff.html

JS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtpmwiigsb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtcznqyifc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hammf.cn/Article/details/gthnbzkwhh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrkzdhlt.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtcwnnqpbq.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gtikigbxbt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjteqxzac.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtcerinoby.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtovpepecb.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtoekdgeud.html

Py:   str(uuid.uuid4())
来源：http://dali.bjfxy.top/Article/details/gtlylydfeh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtyefwztra.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtksusbobf.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtuqdhpwpd.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gttymyyvkj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gtrdkpckia.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtdnhleycg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gtyvezydiv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtyouuofsg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gtievomxmy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gtozxpyxak.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gtfnmxqtoi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gtingssrje.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gtesndgrjg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtpmtneqnp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gtugdgaqen.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtmvhfbvjz.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gtxefvhzkc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gtgjgerkex.html


<!-- 参考信息 -->