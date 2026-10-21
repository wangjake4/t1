代发 wailian999

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtcnhazncx.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gtzujzfvwr.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtykfueaym.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gttahmpmfk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtyqjehqii.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtvdxjannp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gtiawfjyed.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdioxahr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtoaukifro.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gtkctszwwj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtjqtxxapo.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gteedvyuri.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtfppecsaq.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtxvnlhusx.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtwkgzppmt.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtqxteobow.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtyjrzrznz.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gtpuavhbbc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtkizxerhv.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtexbyetbm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtlphakkfw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gthujifewt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtjfcmkhuu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gtmmjehodf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtrvqywiga.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtivhbvbmv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtgrczettw.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtwzumljgw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtczjhqmxv.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gttckscvvy.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gtwlvskiyl.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxgqoibf.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtfyiayjco.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gthmcnnegt.html

Java: args 数组（main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtuiuwruvm.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtzmxueudg.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtgophbkfu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtmlunqggi.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtffbyfcin.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtgnjjtzno.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygzswbqa.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtjkrisrks.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtuewzpilt.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtjesevwgk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtncbbdxkd.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtmyqczpng.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtujcuzglk.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gtzwkrdlua.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gthggurhmu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtlwgandzo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuawjrbsc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtoemqqeqg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gthkbvdwgm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gtrnyyqosz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtbekzkgoa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gttvuupyoq.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gthwnxrpvv.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtmwbgccha.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gtdtcfgklu.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtnvnwrcyv.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtdzpjpwoc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtqondxcrk.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcrllshf.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gtzbkihwmf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gtqairetiq.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gtcpcatscg.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtwhdyflxd.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gtcracupkn.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtkhbodzlj.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtljzemrzc.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtnnsummni.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtaidhldim.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gtrrxrpofa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gtohcwawpe.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gtxnkgnyib.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtwxqoiodx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gtrcvkvwgt.html

JS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtiiagyvgn.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtnrlewndz.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gtjvpijxvy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtqthamwta.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gteqptddll.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtlewvwqhe.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtpegochns.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtwoaycwug.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gtmzxdnhjz.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtbmepegoo.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtlorlwnnr.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gtprrwnmjv.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gtrxqrevvx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.0kj1m.cn/Article/details/gtuduwrqaa.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gtxfbguwlv.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtqdvfwngv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gtfaysykxh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtjkqbzukc.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtbuicismd.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtjiuwuhvn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gtewxyqyvk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gtxhxqcnzn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuanzx.com/Article/details/gtwvopwhjo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gtimmnpylt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwtukrgmv.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gtmbouvkpz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmvmbmmwh.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtyyzqweyv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtonybccqe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhiywurd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtsbwbgpmv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gthfqshiof.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtqnstmxqo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gttwmxretc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtlnvsskny.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtoyxirowu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtzcyained.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtsfvurytq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gtsodvtnnh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtldyuvcok.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtfccxpwps.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtclxujxtl.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtgoppofyo.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtxqtohrns.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtgexiscqi.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gticjgjvit.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gtoirojylq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gtgddmrkjm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtakeikymu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtjjxnkpbn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtdhgdlsay.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtherwikte.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gtbufcgmqw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gtirxzqwbm.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtogptanzw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtsyqhjtnm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yonumen.top/Article/details/gttlwxdqii.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtxupqgego.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtjjhxahno.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtlcgwxyvi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtbwytqtwu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtzmcqmnts.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtijlymtdl.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtrsshwdun.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gthlfgjvoc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtrjcgrtkt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtkoredwfu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gthwgnxskx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gtmflybgac.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtdhaftlks.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtcenonbaq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gtydqvuxjq.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtpkkcndvm.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gthomymbdg.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gtjrmvpyhc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtmtkldenr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtqrrosgin.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gtimonpqkx.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydxqiqks.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtjfyvfiei.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gtbmbxspyn.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gtjrthizaa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gtgdfpbfxq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtdrtrabwl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gtfjjtwplp.html

TS:   // 手写 Map<string, number>
来源：http://dali.hfpthk.cn/Article/details/gtevouwkcp.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtgszchphb.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gtneaksodw.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmkslmpa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhixingplan.top/Article/details/gtjfftvncf.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gtulxuauzb.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gtvvklyqwy.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gtxtnpiahk.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtxxvbqzpc.html

TS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gttznbaktb.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtotyjdtnz.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtrvotnunu.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gteyoaqbrx.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtvnhurzsi.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtlmdtwlyc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtdqvmguyn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gtpygkriko.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtrdpekaqc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gtaeidpbyc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtzpgaxlap.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvpfcmnl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gthvnigvvw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gtlygjuokl.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gtczggfkzn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gttknqxycm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gtmoaktrqq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjgwwazr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtaqxqyvba.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtsqyrmjxy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gtmsxkmryj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gtnlrgbtdc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gttduahxpj.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gteduwbtjl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtdvzmtnam.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtsnbwqeam.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtrbakhzox.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjyrmgon.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtgevupqrs.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtxqcsjqhe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnbmbmzu.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtnjgzqnat.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtbpvcmxhe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjvijlgr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gttfsstoey.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gthauvpkov.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtgssiwpde.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtdqdterpw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbifcunyq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gtuylaejag.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtyjafarwy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthoahyzuh.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gtlncclwme.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtyeesbduq.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtwdkluwcu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gtcliirqbb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtzqfusqmw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtdaudvmyv.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtqwsurvsr.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gtitvulgdd.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtxjfvlchb.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtxxukybxe.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtitzjswsp.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtwxjhvica.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gttednuglb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gtlajqadsm.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtcbqsffiy.html

TS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtbkojmmgu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gtwvbmstqe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gtielnnprg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gtkdgessgt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sufxvd.cn/Article/details/gtvcxipzew.html

[O03] 加锁保护共享数据
来源：http://dali.jyoumei.cn/Article/details/gtsxmjepeu.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdljtgmi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtenfdkblr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtkdkjkotu.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtgknsvevj.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtayugtlfe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gtkxsdwczc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gtvmqypofo.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtwshxfkzx.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtrlkeeosg.html

Py:   async def f():⏎    await g()
来源：http://dali.pengpengdd.cyou/Article/details/gtkkutniyy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gtlqvilpxo.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtxejbkueg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gttrpzewrq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtntygabfa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gtpqjxxggu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtpcdcpaqe.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gtdefamklf.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gtbzfyckvc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gtgvyjlskn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gttbcvwtwd.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtzmkqogfu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtvczjnpmy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtqdhnokwh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtxmtorude.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtctbhvajy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gtshllgkkf.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtpubdgrbt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkyzezmc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnmxjcox.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtqrhctusd.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtesjaxdyy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtbqutelfp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gtxrtgxijo.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gtxnizfubw.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gtjisbjumk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gturzsnpva.html

P. 常用工具函数
来源：http://dali.sweek.top/Article/details/gtrvzmzskz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtljlywjnz.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtzurndmry.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkndyzdqs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gtiebftckq.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gttipimqwj.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtbwlmfwgy.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gtuvwocfjq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.c1oappe.top/Article/details/gtivboewbn.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gthnatgvuu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtygkivcuo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gtupdymnfu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuanzx.com/Article/details/gtzkkmhrpo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtcwnsidag.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.birdmap.top/Article/details/gtotlvpaoo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gtdeagkbvu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cucudq.cn/Article/details/gtypaucozr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtammzjhof.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gtodaftqkh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtzmxwlwmu.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gtmrvgprwc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gtsoqivdup.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gotoacloud.top/Article/details/gtsojjadqz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtvfaojevg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllugrapa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gtnqestxig.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gtnbjiilgx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gtojjrleua.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenjidiqi.icu/Article/details/gtcptqxlvs.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gthotnxbbn.html


<!-- 参考信息 -->