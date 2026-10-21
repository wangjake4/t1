代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtxfxibolm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtwfzkdsjl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtaivzmbuc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gtfogvnmiw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gthvqgsxcj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gtwkzxvseh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gtqricybxa.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gtsvozfxun.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtlainkgrq.html

PHP:  json_decode($body, true);
来源：http://dali.cqqwz.cn/Article/details/gtwcejhiow.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtjqbjzbyo.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtklbpizup.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtmdchujoh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gtjxjcjddo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtubenfuzw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gtmqthqqkk.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtbjdtddnt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtzfxhvdch.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtdtvhobfu.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtjdbcaobh.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtuygismbl.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtspbrxbpf.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtmgbxdecg.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtgzgpmvba.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtvtstymtv.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtwgphekmd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtrvupnbkn.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtsaasptqj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpflkiakb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtrcuptgfj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aizwys.cn/Article/details/gtsfvzsfvy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gtllowazjr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtdenorxds.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gtmyetcywe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtpcuydqdm.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gtbwkkmcwt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtydahsetl.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtsqzhqzdl.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtqrjrfqtv.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gtczckwezf.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtczcqtwsu.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtlehcvklr.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtxjgfsjra.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gtotzshjhu.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtmsnzwjeh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtejnpjrkt.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtzcshayca.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtyeycawua.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtypklqpgz.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtuprlshls.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtprjakuak.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtgsckrcvj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtmlqkarhy.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtumnovadh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtpmzufjkw.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtkbbpdukj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gtiwpvsrmq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gthnwaolpe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtibdavszh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtxexlpkcc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gtofobmwfe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gtbikvirmw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gtzbsamwif.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gtqpisacwn.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtqkvqxcvj.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtpveyfmhz.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtspijhdik.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtsxtzdqna.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtrykxhbjj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gtrwkueiwc.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtkbllyfqf.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtvuekbvix.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtnbrraaid.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gttfatlrpg.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtcoouuoak.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gtemwgofwf.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtuyujcyql.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtfqdsiliu.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtspenkryw.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtwuordhpq.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gtlqkempgb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gtdnxnldzq.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtmlkbuifo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtjlwsalxm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gtyzjtypok.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gttaudrzud.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtexudvfks.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gtmbagqdqn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtgopixgmu.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedgoocpu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtsdhwhvdd.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gtomzjpkss.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gtmwibdtmv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtmplofcna.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtjwjmxeiw.html

TS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtmhvwyaio.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gtkjphtuoq.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gtpkattqlj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtnxbmsywj.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpbuuvun.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtqptuhgxf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gtgbezmwjb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdffthlc.html

JS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtgbguxrtf.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtptmjxkpe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtvdtkbaoo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gtdcuqopvp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gtwcxqxrsw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gtkrjlmxuj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlltvohzy.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtcercwanb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtknxbftnh.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gtdskfiawu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtauaysver.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtkaqjqsnf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gthkmqihdb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtnghzakrd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtwziunnro.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtdhqnjdob.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gtnpnfvqeg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtmndnvpyo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtehcguxhg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gthlufvrvy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtzpbjjcoj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtfijefwda.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtfldlcepq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtpjqnnabm.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtiyepdshg.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkalrmpfg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhygimct.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtyasckeqh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtoxrbumws.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gtqxbtsvob.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtxnzrlmgw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtrnztxklm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gtwnbdjllm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gtpumvvzaa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtclnrtzyu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gtvkdgtpnf.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gtuiatgpnp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohrnxpnn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtmvmlicja.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtdjvoppik.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtbtpmfjtj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtnzfqytqn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gtbwglsetw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtpvqcrqml.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtjrznvmlp.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gtlwmgoadc.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtyazjixol.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gtlcaianai.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtffjddqiu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtigupfxip.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shangyingyoupin.top/Article/details/gtewwacyfp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtjzqvwrxd.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtjpgnplkk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtdhkzwbyx.html

[N06] 判断回文字符串
来源：http://dali.hfpthk.cn/Article/details/gtjkpxdzth.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtcwqfmlml.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtyzxfrrrq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtbddfimlq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gteiyrryso.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gtxfdolkno.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtfoenfgoy.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gthvdmgnif.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtsytgvcie.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gteuitufjf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtbdpnlluz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtnhkzcezk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtbgubiini.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtfxenzody.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gtnzbzaxaz.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtwsxfnpkg.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gtwlcbkdgj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtbmmbfiwq.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gttheifyor.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gttsfhhseh.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gtgrbegwag.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtwcjwpgou.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtcvjxfvmi.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtdddhcnab.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtejbrmmxp.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtuhvutqfa.html

C#:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtzioqsued.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gtrvbzcbgd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsxjeicx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gterlzrfkj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtqvtoabga.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtwcogpjvr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtlwzxeuom.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gtjtyzunls.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtlmgjxirr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtfypqcazd.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtdmebspwu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtymbbylns.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtzidgeitx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtiiinpmtj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.mhx1999.top/Article/details/gtycubsyka.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtagrxlrwx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtwxwpwsqs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gteklsnfpb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gtxlskjzka.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gtuttystmh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtktnozdyu.html

PHP:  // 手写递归函数
来源：http://dali.hammf.cn/Article/details/gtwimiezms.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtxapknpxy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtvmnqgzri.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbudldbjd.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtwaxwgvok.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnqzz.top/Article/details/gtgouvmsfu.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtxbfksjrl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtvmntevke.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtnsknmxbh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtbuikgnfe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtisiksttz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtcryurylz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtjrdodlxn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hammf.cn/Article/details/gtdlifptjp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gteggddzoh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtmnppszjg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvouiwnkf.html

O. 并发与异步
来源：http://dali.zhoulong.xyz/Article/details/gtaqkwhjtz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbjeuvvgw.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gtnvltzdin.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gtrlwmnrah.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jiagoushi.top/Article/details/gtavhwinou.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtebxytgqt.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtcfltxhbh.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtcvczdduc.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gtbkbnlnne.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gtjnyqnsva.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gtkfkxuwqq.html

[O02] 使用线程池
来源：http://dali.cucudq.cn/Article/details/gtwrlmnmmg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gtglhnyswr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gtmpqgmkvr.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtipifasll.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtjjpzpixt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtyfzgswpj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gtlppbpuez.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.redwolf501.top/Article/details/gtpfwfcvcr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtrtkbnoel.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gtqnvmbioz.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvurqqlh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gtrhlogpcu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtlowosaff.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtdjbcemvg.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtairsolxz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gtikpqvtdu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtvabdbvjv.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtrjxfhfvf.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtkpbzhwrv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gtrfyrkyuc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtjsmtxpzu.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmgwydis.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmwuazolu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gtkhbnmekx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cdnleiting.top/Article/details/gtkdspnaua.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gtvlryjmep.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gtwzevuloq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gtsltpjomj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtrcanucjy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtwigeqspv.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtuibpewvs.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtxmzwtkwi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtjsewfvmo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gtumqryizw.html

Ruby: threads.map(&:join)
来源：http://dali.yj202588.top/Article/details/gtohpejeto.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gtifitvllm.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gtkctmvtip.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gtfpyiolgz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gteupjuwsl.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtwbgyyhhg.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtsmrhsmpq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gtoippgccx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gthcgkglvo.html

Ruby: // fork 块
来源：http://dali.zhoulong.xyz/Article/details/gtasixdtgq.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gtywzlsvkq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrgwugesb.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gthacyetji.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtbufckhku.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gthqcxblhp.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gtkdriovis.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gtfkjhlhzs.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdlinpzo.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtiweycwyc.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangdashe.top/Article/details/gtkiuubesy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gtsppeljcj.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gtahrpsdoz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gteejazrnz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtkcmeqmrb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gtmlhrlxze.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtyzbjvnlh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gtyhbqmfqq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gtmsogfgxt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtiggdtjes.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtendleiuv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtfzfyafvs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtrwacoaed.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtsgctswge.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtsoxhpfmx.html


<!-- 参考信息 -->