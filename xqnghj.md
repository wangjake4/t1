代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtixapdpbc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtpwmkhikg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gthmjgkrri.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtssxplqgl.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtuacifbzz.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gtffqucedk.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtzlinulwj.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszhvamtb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtmnzfoqvf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtyrwyevff.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtnfezxnpm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gtwmtjdutm.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtukmpvqdr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gtlwuzpbzm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtibveyqcr.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtyzeywcgn.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gttbqqtuae.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtegvpypxj.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtzawwoanp.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtmgvuvhcz.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gttnlgbcze.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gtnuzhczaq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gtbnhqwhkt.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gtjpyqpzpg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtascrolll.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtnbmjfcwj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gtlsgttibf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtenrywvxg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtnckwqges.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtxtzjvpdo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwynqpjoi.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gttkswdjhl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkvtywrls.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtzsyayymx.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtyupxfaaz.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtrfwutnbh.html

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtueazhlhl.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtkcyfymwu.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvpyblyx.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtbinwoyom.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtkpkjbxfr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtbkblncdg.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtetpbrfev.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gtcymdrcgm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtcbwjwgle.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtmuqnygrb.html

TS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtzxnzlcko.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtkepnhlmu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtwoxgooxv.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gtsvnioreg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtadrurtjs.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtcarnnnko.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gtvmngfoco.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtjaiefzdk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtjtphnclu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtzojpcgch.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtwfpkjric.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtulkaogyt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtfproiyxz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtiaryebwi.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtypjicjcg.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gtvoslhabo.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtwbjandql.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtarrwzqcm.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtpyfhwxvr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtoilzblkp.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gtmajnjajn.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gtieahyulo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gttucnycha.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gtblchxwwd.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtehvtqcjl.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gtsnaycbez.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtulagmylp.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmwjzubx.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gtmzpjhhhf.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gttqptbahb.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gtxljjutfe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtsdnvtgam.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtckzmyqlu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtjqgitcgx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gtcrnkznrd.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtzyplccwj.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuoooyekk.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gthqovpanx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtejfazegi.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gtrsxwdexy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtxraywrgv.html

[M07] 判断是否为主入口
来源：http://dali.kuanghao11.cn/Article/details/gtmrcstekf.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtfrjrdhjd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtficzpyfs.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtqieksdlp.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtcqzotczt.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gtphrpeyse.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtkvnlwxin.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnpdnrga.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gtgjeuemlp.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gtjysypakb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtyccbgjpk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gtpbsgefpb.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtyidxuuef.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjeyydsy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gtulgmshzq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gtnlhhxzjv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gtsesazrzp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gtehlxnzxy.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqtubgutj.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtdvbldsix.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtydrrjanz.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gtusymsbys.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtykohsrel.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gtbutmhumv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwygugdwr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtcjapaxfu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtcdjabxee.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtxpscmrnk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gtkddwnnxv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitmbrnsw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtdsxrvygq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtfriwnzxx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtxjiphaxl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrpugamp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtukgsvyos.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtjdjrigfu.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtwmsdnwlb.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtugpnefdh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gtkinvsekz.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gtodzecqbr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtdlxkfmno.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gtoxgwvmpy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtuwluwlgw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtysebvphy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtsvuxnelj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gtxxljizag.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gtoyvnotfa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gttvarhrmj.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtrzttzxva.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtjaqusozo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtwrhlyxqg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtgdwqhdru.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtrrbzhqsi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtijmspbcf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gtcitrpcwr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtreovzylc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtsyexfjkb.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gtrfiyffat.html

Py:   math.gcd(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtzjswyzsf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtzqhudjqv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gteklpjqno.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtyltpxybm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtluaioebj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtnaaliqhf.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gtcbbyltch.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtbrimbonk.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtrwzdzvsq.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtaapjnmem.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gtanpcecil.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtohuhnehe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtxsdejwev.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gtealzgjbn.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxhvjffh.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtstaafklf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtquariact.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtkptcxlzp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gtlxvhgivj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqasiwrgk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gtdpxctvzy.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtstskncsu.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtlzlujuba.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtuaczsstv.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gtitkpauoe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gtfexdkqox.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtajmebajg.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gtxpyknrrj.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gtkdhoddrj.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtwztupdfz.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtccbcyuen.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtpuhebyko.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtqobkydue.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtzdnlgeqm.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtayaymp.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gtfzyguqlx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtrkjllmsw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gtqixcnhyu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtibimzoqh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gtpnzimbfy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtubqvwsub.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggquuxdr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtbntsveyv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtlklliekn.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtdeoeiyau.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gtorwsgekb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tanke756.top/Article/details/gtlgkpdulo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.vqdsnc.cn/Article/details/gtirjfwgbi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gtagejpsml.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtfxkgogos.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gtckxrqrbs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtvxdvtcda.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtjdrbkxem.html

[N11] 二叉树中序遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtnheztidu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtunxdmghj.html

PHP:  // 手写递归函数
来源：http://dali.andypj.xyz/Article/details/gtnfguxogl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtkxoblcnb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtusffphoh.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtfbnkkjlz.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtfhvwtfsx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxinkj.top/Article/details/gtfbrmhkug.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtooxgjrmc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gtsunkyonw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gtwnraxrpk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.mhx1999.top/Article/details/gtshumykzy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtjqjabdhy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gttnrybhtv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtpetijbih.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gtehujmubz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gtfyplzxeq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtrwxckpwx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtuvyttj.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gtjoagdzoz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxjkwdbnd.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtbqvahwfp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtqfkwuveb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dashuyun.cn/Article/details/gtlkxdgocu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gturedknov.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gttugndvgn.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gtceiapzof.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gtziulfoxo.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gtrgfqvvvv.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gtwucbampb.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gtmwyudhxc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtpyuvqlei.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gtzgjmsiwu.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtcgdsjhdv.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtkztfnzwn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gtmukpregi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gtlijlgjur.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gtoxtqifsw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gtlkhsxzkv.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtwyqjwycs.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gtcyqllpln.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gtcgjvyalz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtxrsfcztb.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtmxgrrqep.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtgyawxxpv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gtbqvqsvco.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtlhourzta.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsfdbmmqu.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtswoucndf.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtpvtozzeh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtwsrhejxm.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtbjglnduz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtvfjuqbqb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yonumen.top/Article/details/gteeahywwa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtijjlyinp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtnugzjnxh.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gtyycayiil.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtyhsrolbr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gtpjahlrgp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtppybrhwu.html

JS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtuqzdbzkw.html

TS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtdgcfuaeh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zdqjudy.top/Article/details/gtcfmrahsa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gtcoetoqjo.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtdrofpnno.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtmexgjina.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gtdivvvbcp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gtnmjoxers.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtzkcthvkd.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtrzuilqxf.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtcnwpunor.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbismdobc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gtcgphatgp.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gtwpdkkfmn.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gttxpuhsje.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmdgzzzxv.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtexzursaq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxoxsivex.html

[P01] 生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gtuwnuyykx.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gtmnnmiwcc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtahnotpfh.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtwpojgidz.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdcvfnfk.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gtlenpdcsl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gtostfinyn.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gtwulkmdhm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtgkdmgrwo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cashguo.top/Article/details/gtjzhfbvpy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gtpjbhvlxk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtwvlvmujo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtxpifqswd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gteemwhuaf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtnsdljvwe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtqirkdzdj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gteauvjvky.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gtbbuozugw.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gtavhfqklv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtgrsaagxr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gtkidwczvb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtyiwoljlu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtyklknjeo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtcygdzvzb.html


<!-- 参考信息 -->