代发 wailian999

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gtlupujyto.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gttnycmkdf.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtdcypfwie.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtufivwwuu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtzvutatfg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yangfankeji.com/Article/details/gtkucvojbg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybhmgudc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgphcrvc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtwpttafkh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gtpvgpxugf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtyssacpjv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtyiimkvrc.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtkeijdyka.html

Java: resp.statusCode()
来源：http://dali.jinqigufen.top/Article/details/gtppfsxadi.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gthtsrolix.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpvyxikl.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtjcsdfhuo.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gtfkachffe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlidrjvu.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gtrhkkdrar.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtzkvyeyru.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtcunnspxy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gttcardjoh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtpuemeabo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtpldepckq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvhxaafw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtuwpusvkz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gtefeuymaz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfakoehre.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtuyuxerwe.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtoxsmyczu.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtvxthaihy.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtqgoynfvf.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhnlelwg.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtpuithoxx.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtivsatcmz.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gtufpsjjtr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtrbbojgcl.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtddsyfzsf.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtzrlatsdw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtmptnlubz.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtgkezvavj.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtxeclvodr.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtgpwmzdvz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtvmprxwrv.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtnokirvyo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtacyoquyr.html

[M03] 执行外部命令
来源：http://dali.yongpay.top/Article/details/gtyxevnuoe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gtddovwjnv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtsfhuedrr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtieprzjol.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gttqztevrf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtxffgnfpr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtmpinwsvl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gtruozhvmp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtxyiqixjf.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtpywkvwum.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gtupjctltb.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtxodvfnml.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtqfhffhny.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtmmvixaxr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gtwvydrlkm.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gteyubigxx.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtbxvmajfo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtoegweumm.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtytndzaos.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtommudica.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtyfmsnidk.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtdtdqreei.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtdrbnmepb.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtzfiautkt.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gttledjnwd.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtijtomkjh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtdrzappgu.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gthtobyion.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gttpdafxbb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtmmylbhcb.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtaqxmmdih.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtqhufvbwx.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gtasllchux.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtrwwyjdry.html

Ruby: warn "err"
来源：http://dali.sweek.top/Article/details/gttjcwganx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdraikmy.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gttehpwqir.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gtkaznqfgf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtfsgzgjfd.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtbercosfa.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gthoqihxry.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gthcjzlqoz.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gtbihamzyu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtkbohcrtp.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gteuesrdju.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gtkzlcvhkd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenzaomai.com/Article/details/gtrlwdgdpm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtcemonyrt.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtcuomfekn.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqsekvrc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtehxaupkx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gtsvnfuutn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gtktamdgse.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowwtmjks.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtehasbtas.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gtxlbkzvzw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcraygveo.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtfxddkttu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtokpssrkh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gttuzdjpnl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gthiqqedfs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtvmllwehk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtbqqtcloi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtgswkihhu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlygoszfy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtmrpplire.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gttheubiri.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtkgsyvfnq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtxpwpoube.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtgtmvfjjh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gterxmynyh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrevdugxd.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtydwzkuut.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtlsfnhkrd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtffvsvqiy.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtkxmmbpji.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtzetamvyh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtapllkhjs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkceqmtll.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtyopouydl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gtsgeeidwa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gtpheobrcw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gtqupgdiqx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gtwccdzaer.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtnuyrlzoj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtppoiwohk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxebrjxyq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtsaezhrmw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtufctxppq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtidpvnvjh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gtqnkhuanh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtxlgktlsd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtrcmysfau.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gtxvfmihpg.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtrqttnwkz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtsfohdlsq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtzmppxmjb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaxybtnf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtryucpgtm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gtobjabscl.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtxzokiwrk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gtcjqexzeg.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gtbvpfwlkk.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gttwktiiiw.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtnytgeqjp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtbfmguaaw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtzshjpgzm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gtmeqvedun.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtglwcsezg.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtpmmvythv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtlcpaanlf.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtgctcompr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gttlcpqquk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gtlvsielfy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtftbdiwyg.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtlpmsaebs.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmlafvvv.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gtyozdolnj.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gtmwsjrmmz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gtywipivuz.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpzfzitq.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gtbczoubzq.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtcjpkprdk.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtgvdqeagh.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtwxxfmybh.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gthqkwcgrv.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtzsbzqimh.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gtgfeavfdw.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtkxvkemzi.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gtygjbhugz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gtufsxqmei.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtehzfiitk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gteaqlzlgc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gtwiegrbem.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkantyhfc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gtbukzcmxt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gttllhxift.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gtfuvqxrtz.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gtuletffkg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvipohst.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdynmxjjh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gtujprubrn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gtggnxnvwk.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtepovpgch.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwhmuang.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtggqbmbtp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtqfqmgwyp.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtreilrryo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gtwhuaqeyv.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gtwsamqqqk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtwzkqmyng.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtmacucegg.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtghyehmvl.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtzckwgwtl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gtdurlulfp.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtunqbbawa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gtkyhywkme.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gtvhszjfnl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtwsfxeivr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtspngtmbv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtolqswytj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtusmsonng.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gtrwrrfaoi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gthwnbkaru.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtpdathjhz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsgjmcigd.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gtcpiyyrzf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxreofude.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gtwwhswugl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gtqvtpvqhs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yanxiufei.cn/Article/details/gtmluhwekx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtbujeoddv.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtzehdxigv.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gtnjerukrv.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gtabfcfgle.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtpcylnjiu.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtrxpzuehd.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtnmvzwdzm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gtncpcjifq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gtkwetiqth.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtsefnpunm.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtiupkhhvy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtewksgczu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gtnssuoekk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtlnvldfrl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetagnlgu.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gtfquoabgy.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtfqxfvapf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gticdnnejx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtwhsghjad.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctyzvdpk.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtedhpfuug.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gttdlevpuo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gtcjccicol.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtacpnecie.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtoxkhxjxi.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtjkrjsbiz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gtmdwhngnl.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtjdpkjoyl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gthpyjmzhd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gtcdwjnomy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhcbwryl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gtyhxbfzlo.html

C#:   async Task F() { await G(); }
来源：http://dali.c1oappe.top/Article/details/gtwnglrfph.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtaxlordas.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gtnsdyzfux.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gtxtnxegps.html

JS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtbwozkcvt.html

TS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtrhumwtgc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosqzfuzi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuanzhike.top/Article/details/gtylknkbqy.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtjfzinweg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtxeackdov.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gtmlyvaixv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gtcyxigwuj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtauymzxhb.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtsztgdbop.html

TS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtcjwggpwx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtjjgeerbh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gtgomwsaxn.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtquxzrcuh.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gtwkmjkbda.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbakgpvqd.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gtlnkkbngd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfxgcvbep.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtnwloujef.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtrnrymjta.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtxqjvgpeu.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifmhtuse.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtqlroifqv.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxinkj.top/Article/details/gtwynaoikn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gthbjtjsid.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gtoczqjxlw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gtihecmzxz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfwbwypr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gtzhgjldab.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gtghzniqsq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gttjuqsslo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtmuqwhwjq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gtizsruumb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbwznkln.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmohustiv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gtypwdmqae.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtoykpotyt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtazeonumw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtcxbuteoi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtxowaweig.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gttbpnuihm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.redwolf501.top/Article/details/gtcuklbhlb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gtxhdetvcp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gtadcnyvne.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gtzrpwbzio.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtffqrxioq.html


<!-- 参考信息 -->