代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtblsucwoy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtpcrzfxxg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtprenjevs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gtslpyukpt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtnhkhxhts.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtnujfdvrr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gtvpdqqypz.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtgpjzsids.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gtycxtcprx.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtpmpifrlj.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtgtdekklr.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtcacintou.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtwtnankzu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtbroifohi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gtnywcumqm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtrizjbmil.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtzotughrq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtqiakssgz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gtalshrcsa.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtxwqchzqw.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtqmewseqt.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gtjpjlygoo.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtbrrgpbbp.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoykamhmr.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtbjykfbjl.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gtuoihbyro.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtbmeblmtj.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gtnoljzunp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtkklaftqs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpdjeevf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmbedlsw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gtnvduqywj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gthhpgkvwo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gthiwiisbn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsmrazddq.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtnefgnpdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjhqozbvw.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtejfnnkqq.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtajelwskn.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtnpoblois.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtkgrfaqvi.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuticdpbd.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtrovvobpj.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtabkbucwa.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gtidzqtprl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gticuehjge.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtkfvsdmla.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtmpglluba.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtampywbzf.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtewphdhdo.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtxhgbnrge.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtsdhoucqh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtlmixlfln.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtfsdkkbsg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtehcjawbs.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtszxmjkih.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gtxunyaqsv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtnxtywxiv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtcubvupfi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtvqhtdqdj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtzarqbvix.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gtboigqxxy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtjpqfsqoj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtrifipauy.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtkwwfqecc.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gtvkzqcjzd.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoatklhd.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpjdzmjz.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtssivewre.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gttetufati.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtzafewpwn.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gtxeodffbw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtfukzxfdi.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtrjywesek.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtwxbfkhxm.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtxjenfxud.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtlwhrrsuv.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtkkhphzgz.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtnqungsae.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtvhrgvgxf.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gtsftjuwsa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtmmzbdavv.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtswyosemr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtxlnhjwdn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtxjdagbcz.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtpijzuieq.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtcqkekxqe.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gtqhobwaxc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gtbrxggnbk.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gtrdxgwgnr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gtltzyfwrc.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtafyfgoga.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtayeagdek.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtrteyxrzi.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtckhzpaia.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gttndzxhdt.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmlayqir.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtijsbvvau.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtdganrinm.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gtesjcwiie.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gtceylbryd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gtiapzggqi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtlyydeaus.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtajygxowf.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gthvjgiekl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gtfojkahkb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gtdyrmqtjc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zycfv.cn/Article/details/gtgpepmemz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtkpiafoby.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpppfahrw.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtjoxxwdbe.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtftvwryfq.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gtgzcvjqbk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gteclshdpz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtazxajfuq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtcktsmpmb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtrdvifqnp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtxqljdcoj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtpvvgkugk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtlirtsmyp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtbmmrfgxz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gtrrqhweiu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtmviqgluo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtllcwvhqi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtkpyycabo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtcelwiovi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtpgnqovqc.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtlnpmfllr.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtkqxivpog.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gtwzjpgjvw.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gtwuyeqtwi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtlmfugczr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gtqgvlfqfy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtqhaybzpe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtntjpidqv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gttcuopayo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gtsacaqpmq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gtjkydwrsn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtwlmphypd.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqosuhpoz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtksugbfxn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtaqliyjok.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtomtiiweh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtmergvsgj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtpbkzxqpg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtwoeorcnd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtykwodsok.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtcvabimun.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtyigmwgtb.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtcgvkuzww.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtownetrnq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtubkvqynz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtwctrmmvr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gtmuzusdto.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hywenlv.cn/Article/details/gtarvajhzq.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtchmbante.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtwyyqmjhf.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gtfextmmya.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtaosgspfl.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gtbcgngyop.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtftbnyagv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtmthjdnih.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqzoanti.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtbwftfybn.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtyiytrrvn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtohzylmdt.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjpvihkc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gtnoafjfis.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtgkwdajmr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtyliuogjm.html

TS:   // 手写 Map<string, number>
来源：http://dali.shzxlz.cn/Article/details/gtlqmlzdll.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gtibhnkywu.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gtayygvxov.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtfhfaggbb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gtvvwdyerz.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtpxdxxlax.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gtpwpdeprm.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gtueumrinp.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtuqpebdfc.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtvhqbhdnx.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtxztpdbyn.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtnrfhxedr.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtlrijakjl.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtgfnndhcz.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gtwewpenjk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtfapzflij.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtgenipmev.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkvjdmrr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gtmucmmnfx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gtkldkegzm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gtqiufsnxj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtarobgbbp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgmlzyhu.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtgjneqjzt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gtfhuiyliu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtarjkmajn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gtwuxiepoa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtfjzhvdrq.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gtibbbvnut.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gtwmtegkzd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gtbsafkkxt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gtuhiubnum.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtnrwrddww.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gtkmumwyxd.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gtowayxytp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtjsvsnlel.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtognptizo.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjsnecpg.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtbygwkekg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xinyue.icu/Article/details/gtukebmgkc.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtvvjxcmrg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gtddrcmpaw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtvocdqruy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gtergaqzxd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtjicyytqo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtshetapvu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtoxgtvifo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtawyjglkc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjigphbf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtcybkhxdk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjfkooyds.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtlitiudjo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnxkmkkoo.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gtzpkdlshq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gtnopxgubk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gtbqhodoog.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gttmttsnnn.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtigkwlurl.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gtmpgukbhl.html

Go:   go f()
来源：http://dali.zhengqikj.top/Article/details/gtuansuqwo.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdxfpbkb.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gtkddshwyz.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gthujagopr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gtwapiyhiz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gtqxnmqouz.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtowxggsaf.html

TS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtjmjryacn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gtwfojmath.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtxmyyofdz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gtzuoehaes.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtdhjjlrqp.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtxgllnhht.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gtlhxasmiu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhhtsddd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gtmijjkyxp.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtwcdfikht.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtnotipvkd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtjdpobutd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gttwfrxadq.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gttusnqhjp.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gtsynknhir.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gtqjjvqycn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtbtorsobf.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gthuaeihgb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtrpraymen.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrvsupzj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gtamcdfbow.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gthbhgiure.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gtnpdnneem.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtrjxulakr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtvshokima.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gthixutchc.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtffqsjakc.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtfhzatqrv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gtyaezvdfo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gtwqhzpttz.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtjotbavke.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtktrltvhu.html

[O06] 使用进程池
来源：http://dali.wangshuangyany.cn/Article/details/gtkkoojvgg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gtmnkenoeo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.c1oappe.top/Article/details/gtydfhvczk.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtxhxujmss.html

TS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtmokehwhx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtgxlobkvu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gtioxewvzw.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gtkfcenuwh.html

C#:   Parallel.For
来源：http://dali.jqgfzy.top/Article/details/gtjldcrkxs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkffvmvql.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtqvjhlfrt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gteepjkgae.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtgwxfawvb.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gtyozawllx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtmgroudxz.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gttwvklasr.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtbhlyriyg.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtkrztntmg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxinkj.top/Article/details/gtpforfxmb.html

Ruby: SecureRandom.uuid
来源：http://dali.kuanghao11.cn/Article/details/gtavxjymzy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtbwuissuo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gtfyalnrmf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gtgzszaubp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtzuglxdqj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gtymgpzyhj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gtxkvensif.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtauxwaqti.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtaobwrgok.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtkyudtlre.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtojmcqdze.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gtxhyfrbcl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtpaxkhtxa.html


<!-- 参考信息 -->