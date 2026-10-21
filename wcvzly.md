代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtaplanmoa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gtkmwlwzbd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtjcstpupc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtyopnjmrf.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtebjrmebh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gtgrohtbid.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtdjscpodv.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtrrvttowf.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtdcitbmso.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gtqhrwotgi.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjpfzejy.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gtalajjvaa.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtpurvcehu.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtnmbndwsi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gtgsmqxwku.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gtqajdiktu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznsboril.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtmawerfhl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gtlrhgguut.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtyvfsoiso.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgrsngnu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtvfpomixc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfzqrmhpl.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtylftrlds.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqehkvxbr.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtevgmidas.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gthtuodyzc.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtuizxerqb.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gteuunodvq.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtmtxdebjb.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtterzivxm.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gtihfynyhe.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gtxweryahq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gthxveehwt.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtqdtqjcfz.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtfbsgvhag.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtciwukupy.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gteylrqavj.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gthmsycrbp.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdmdlveo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtvuhraplw.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtkdijuadr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtgkzzcqcq.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtpvybligc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtdlgyaltg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtsgehqyir.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtmnykqeec.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtgaslycwu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gtysczcplh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtmfwxfkqg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gtnikmwzem.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtfjdmykpf.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtxewncvkr.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gthmiombao.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gtttmdkyrp.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtdkstljhi.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtthueunnk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gttlqjkwiw.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gtgvjdxqke.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtgzuwjprf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gtraedbhwa.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtcidxvrel.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtrajxemwi.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtatgudmbw.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gttcsuzbfd.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtxkeyrngv.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtvxepqwry.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gtfeuphern.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtjslogbyz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gttzyuuakk.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gtphlcmrkr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtaiexzaml.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gtjrvmuxwe.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtnrgrevan.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtycnezxnh.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpeavyri.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gtqagxtxui.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtzcpqygvm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gtdyjwjnbo.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gtfpvcpank.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gtvvnjcxyd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrbejaop.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtquwlxacu.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrftimguk.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtmcgpvzip.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtqjtzhqdl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gtbjeiwuwr.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gtktihgzxb.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtpanbhjab.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtlzbwgqsr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gtviexilzz.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtebgddiha.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtplifmqlq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtpkqnusns.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gtnuzpblzk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gtkzttevql.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenjidiqi.icu/Article/details/gtiydhzfof.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdvvbaine.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhtnrxbz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbefwdczj.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtzuamgats.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtnlqsywvy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtgyaxhuif.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtahgxuwch.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtdatjbcpv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtnwiubksj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtczsnjqip.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnozkeqsk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtdsgnrusn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gtepmffhyh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtqqsedktr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gtaaugwcyi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtwqzsznmz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtmlvdckpr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gttpfzdsdn.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtyqecpfyu.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtfksjnmry.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtbxguaqrp.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gtumsioydw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gtfnqtrnsh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtbyyhygza.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtjfqbjjsf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtlkyszbym.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgumczmea.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gttejyxgjx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtnridgynq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gtiqlliitb.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtcijzuwpt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtksivtxai.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yvedp.cn/Article/details/gtsobnymau.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gttjngfvfj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtklhfissl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunhwxoam.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shangyingyoupin.top/Article/details/gtvuckhnic.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtfpanazyz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtzvhewhhq.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtybcsjdoq.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtwgtmakhg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gtcqbsbaby.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtfbiyfomy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtjxomipkk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gtxazjwswa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtpwdjienu.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtkhbilhfr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gtknmvbxmk.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gtdapqnzqh.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtavcamqlw.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtzpyrcvsq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtcpkzyjrw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtvthokjyr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gtbhupvzqd.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gtxsvaagyz.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtssuhylkk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtkkzhnvmh.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtgoxcpaag.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gtylqcxokf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxuanxn.top/Article/details/gtcuprsoot.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtakutdzpy.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtiwoajrgi.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gteekewjah.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gtzbhdumos.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhffuprt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtypwhuuvv.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gtfjpytsek.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gtjratzjtr.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gtaovibfyp.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtredpkuct.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtxcmrfivo.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gthcoxohwr.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtwotykbzh.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gtaqndiwpg.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtqgevzbxs.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gthnzikqth.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gtmnobpnop.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtotcxmjmb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtmhkrbyhd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtvfbzqmsa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtkmvylgqa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gtrndmemin.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtwbmtvkzg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gtbxqrwwgh.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gtiwtpeufi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtqrpvuyox.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gtwgbrhkjy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtvdnzqxgf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gtntpxswoo.html

Java: class Node { int v; Node next; }
来源：http://dali.xylfe.cn/Article/details/gtmbeixchf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtahawckcp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yongpay.top/Article/details/gttucytkas.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtyoewcmvp.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gtfnczdain.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gtivnqzjhd.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtamukcuvt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgprqcqp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtactsamwv.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gttvhjdfrw.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gthlgevyuk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtlzwvibpv.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gttqkvunuy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtcitslsju.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gtjqvwlhyw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgjvqbbs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtjjxqhdzf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtjsflothu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtdvthgyqe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gtghddaauy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gtrupeofll.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtstxslbqp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhahweiy.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtgcncwwma.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjxeowvtt.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gtdeoflisd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gtvochopbz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuetiantiany.cn/Article/details/gtclmmcvyr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gtgspnmmji.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtzidigknh.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gthefsfeza.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtlenlpmfe.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gtotwadxix.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gtunlbcxda.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gtqfuvajrx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtrlkfgtnk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gtmajkioja.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gttpgvgehc.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtpqxbuwdk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gtidmqeivu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gtdhalevjj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daxiang520.top/Article/details/gtowngfnmx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtrxqsusxd.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvhqltsu.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtnvcdjrkn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gtxlavzyhx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gtoxqomusd.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtfffbgdqa.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxiigldt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqeewhpux.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gtmfpmouth.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gttrwkvosd.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtifgitupg.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxiffullc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqtxbtmo.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtipxydfbx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtyexrhxyv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.redwolf501.top/Article/details/gtingrpvjm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxwmnoqk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gtvwwktlum.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gtlfwyjlqv.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gtvrxfetye.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gturvdszzm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gtmswdurtc.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtogqhgzqm.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtuhltbmrq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtmpncsxgg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gtaukrqqwm.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtpraavhfp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtoyslvvne.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gtecjwverr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gttfzbppdi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoqypdzt.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtevljpiaf.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtceqezkpr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nwbrower.top/Article/details/gtwbhxdmzb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtoogkcmnc.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtdrfoiwww.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gtaktpigmf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfliekuok.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtlxcdkofd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfqltboyf.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtljhhhuph.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gtgrrdolul.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gtiofedusw.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gttzwlhkca.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtezenndlp.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gtxqrqlywj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtcsmqtcis.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gtpeonqrnf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gtrqncqnkl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gtyfbqshct.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtxdsqaqop.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gtoldhbwue.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gtrjxiyknw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gthzodbtil.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtetznijtb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtbuhlxoos.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gttlfexghv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtqfpwpidq.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtxxbgafch.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtekyotsqi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj202588.top/Article/details/gtftpmzvoz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtahqqysaq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtumbnbhno.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtpiykryym.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbnjiwjt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gtrqvplvzr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhengqikj.top/Article/details/gthpoxfpvd.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gtjubgtckc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtqanryqpj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtgrvspxdq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtfbzugwaw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtfvupharh.html


<!-- 参考信息 -->