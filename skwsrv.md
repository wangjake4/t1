代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gthnjjtjiw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gtkorkhyod.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtfgssswta.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gtjgbcsryn.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtrvrxnclp.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtaorqymkh.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtxbijhqpm.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtnivssrrb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtbkmqbbdw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtrotiwyqs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtvrwzvyau.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gtfbjcqabs.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtxmlxrfbo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pengpengdd.cyou/Article/details/gtzppngtpw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtvrjttrtv.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtcisemlnh.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtbqyrxefj.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gthfiuclhd.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtaovmkpcx.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtyaqvfbnh.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtlcxkrliz.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gttpxbazwz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtcasrnuyh.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gtoyrlamai.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtnsvkhjmp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtovqyysvr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gtqhsjqwmr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtjgrvubha.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtldamvpgd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gtsyopuerz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrfjkxpdr.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtvwvqwpzs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtbwyqziyb.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtqgokkeoi.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gttecfwyvh.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gtzenkgqyg.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtzlllyufe.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtonznlxxt.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtxztovjwq.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtffxrngde.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtfykazzne.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtsvhmvfxk.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtufegrnzd.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gtfmrtbpye.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtfmryhffx.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtcttwwnvt.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtyztwpskf.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gtlpppmftw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtbqsklwuz.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheefyujp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtntrslkts.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gtrzzletlh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gttqoqcvrh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtblicbrcq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtwjzmcpst.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtelntjmsd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtguktqiml.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gtwmceqlnu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gtymocolkp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gtzdlbnvxr.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtkgxdiihj.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtnqdoxeyq.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtrsprgkrg.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtwcyxbpev.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtgmbcgfmt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtczmnzfdh.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtgolmkulm.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gtracwnkrt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gtglmujccd.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtjxtfwmeq.html

Py:   sys.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtjxcuxunn.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgrnxrag.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtoxfrixog.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtaxopckgh.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtbtggdrmw.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gtdjlthtjk.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gtluhnwzyv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtnuspscll.html

[M06] 向标准错误输出
来源：http://dali.xylfe.cn/Article/details/gtvukzmwuf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtemfyfgfy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gtpdfwnhdu.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtukltzgym.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtptbratsu.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtpxyllgro.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtryafdxrl.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtflscbnju.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtxnhhwzpc.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtzahifjif.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtspductzi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gtbmjdjufg.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtelsyeqpt.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtqfocmuwb.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gtjtiljhib.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gtrdwovyhd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtesvinxkp.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtoxbrbgbo.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtxedmgolt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guannengcc.top/Article/details/gtkxppcyfn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gtfdiuyqqe.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gthuchyydx.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtgsupbdfc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gtnkxwvjql.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtoqiqtwrq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtosrkfdcb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gtamarkvwk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlclmsoar.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gtbymoflrw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzqmyziwe.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtqjskyoij.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtqulyadwo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtmoaivogl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gttqqwgkuh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtkgwuubue.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtadkoxlur.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtqiochihp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtscylpjev.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtirmqsqmv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gtepsvaniv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtjzuoclpt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtvjaqfrqa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtauggxaib.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtbfttgitf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gtnhdspzgx.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbphvhpdk.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gtxzrouned.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hywenlv.cn/Article/details/gtecrlykxe.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gtqwexoxjn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gtfdyyskyj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gtboexoswq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtgyylduuu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtzhfghtcz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtfefmjlqy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gtdffmmezd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gtrptislxt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gtgwbzxlan.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gtgzeadvzw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtwudwgszo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtlxtpvbzg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtxbkrvaxy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtktpcotuw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtbgfzjzsh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gttmxbwltn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtdjwnyzvc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtfthocxry.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gtjusywatb.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtkraqmtzw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gtouzziqdq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtqmbkujfi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtfslsclgt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gtqpuzxyqv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtzxpbvbpw.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gtzyxueato.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gtfsdnzkbe.html

[N06] 判断回文字符串
来源：http://dali.sysykeji.top/Article/details/gtcfdfpetl.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtczvecxrp.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gtbznezdvj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtlzvsrjan.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfkpvaeo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtxahgwfhb.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtowktgcxi.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtyrnkjdki.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtipuyamgb.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gtegfqtwsh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtoqgkmuax.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrtuimca.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gtmoumcemp.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gtzfumkxde.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gtwuvflxmo.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gtwwfmtqib.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gtomafrbov.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtycllvipg.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtqbxhmxvc.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtyletatmb.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gthkrjkvgs.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtqdblaato.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtomddflsu.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtqdnijcmq.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtgxyooaid.html

Ruby: arr.permutation.to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtaapzjyae.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtelweiwbv.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtaqwleemg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtyunqdlag.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtefivkazq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtxfikaeja.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtoiqloehc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtlojxtikw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gtmyesnpvs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtdhqyuqmz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtxwroyvdb.html

[N10] 链表节点定义
来源：http://dali.vqdsnc.cn/Article/details/gtqtlbtyry.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtjhyzaemk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gtbscvubqn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtoiibngha.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtixwxewtm.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gtkuqmffuj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gttavwgdpa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtkfwpydeh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hysaishi.cn/Article/details/gtflyjfegs.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gthaoazlah.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtgknvgklb.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtmhvfbjcj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtccxnswsb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskvexxhl.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtozqrbhzq.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkampvwon.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtgzsmwpyn.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtqugxujdb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtdxvifjma.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtxxynvhye.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gtogjgkhbr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtbyecmybu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtlebzyvut.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtfphlnjyj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gtdatpxqfn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gthotnbdhq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtvpmvysho.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gteukmwcrs.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gtfdatbckm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtehpeibzr.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtcxrkataw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gtyxldrrho.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gtlegkimwn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yangfankeji.com/Article/details/gtoqttlmtm.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtuuoolkni.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gtkrnbmfzu.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtxasypywq.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gtlflrpqgz.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gthinnajir.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtsttsgyic.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtohnbvhyf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gtephbypqa.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoejigfz.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtxqsvzxjp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtfnytwrzo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gteezazble.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gtndokvilm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasbgjkze.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gtgoxsmfkg.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gtibheczyu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hfpthk.cn/Article/details/gtfrpacjlx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yonumen.top/Article/details/gtndotbxxs.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtctbmuvpv.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtmlvwiqjv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gtvwelmgza.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtciovefzv.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtbaiucctj.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtsagvunaf.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gtislfvozc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtsnrpnufe.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtltobmdkb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtowqzzvfp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gtnoeccuam.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gtyiizbqar.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gtdbjyiaad.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gtiiokvzqy.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluxflmjj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gtgeveixlw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gtknhfnmsq.html

JS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gteuskuapr.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtanbsqlsi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gtlywstxps.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtccjkextp.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gtwbkjeqkb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gtynzizhbd.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtrpfajfkv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gtnfdsqbcb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gtoaefgmkm.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtfpqvxtbq.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtptvmbqvh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtthygryjp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffbzwedm.html

Ruby: // fork 块
来源：http://dali.snrcjt.cn/Article/details/gtmdzowtjm.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gtgrxzbwuv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuzkoscws.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gthzecwypw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyazrszgg.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtpbfotqis.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gtaunsuzfr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gtpnwitexe.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtxmwfbxps.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtbhotcrgk.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtavauvknc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtulkyrxoj.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gtpqiolido.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gtkxgknfrd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gtypdcedzq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gttkmxrurj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gtgdxfloib.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgufenzy.top/Article/details/gtlnneeysl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gtpspgfytu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtvjmaxvdd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gtirujrdcp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gttcvazdmy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gtkwpxolsf.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtbwkcvllt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtbmdmjtpe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtyfndrphs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtzuhxppye.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtldzunebx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gtqnbogwvg.html


<!-- 参考信息 -->