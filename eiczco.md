代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gtzrdzxttn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtlbsujzuq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gtzacasvcv.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtezioexmk.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtndfdyxqi.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtjkqypl.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtgqvxgxee.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtglemhtkq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtmjnhvcvp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtgpulbkij.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gtruvmcged.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpkrecba.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtgcuvpiwx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gtohvgasip.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtlscosmwf.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujmtkfvd.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtkbvcwobt.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtwtjsmgkf.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtpkkcjyvl.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtdwlaodxn.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtsbooipky.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gtsjxzhytb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsaognbc.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gtywrdeztx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtebzgokjh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtnyghcuzh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gtjwzsqqnu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtksuzdyjr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gthvudbxba.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gthrzdistd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbuxowqyh.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gtvbssqsok.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtyfdpiyze.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtjkpzalhr.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtlurqvich.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvnopmrw.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtbhmaemlz.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtpygkrwqp.html

Java: args 数组（main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtgdhqcoii.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gtbhtfgdan.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtydjgsvfp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gtofozcopf.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtxubcijni.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtgkmjsikc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtmdleuphl.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtesijmwhf.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtysdwbmlp.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtnpdndhzo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtkuqyyzqu.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtszbbzxuc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gthuyyqier.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtjfryiikj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gtybpwdwzc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtavteollr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtqquiybbn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtghnhbpkc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gttaveifeu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtvqjshtqu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtrflgejbw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhongyouzk.top/Article/details/gtvuimtpkj.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtkkgxwnap.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtkkrfxwlw.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtpxbyzpfr.html

JS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtxgcwadvg.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtyuclmtjp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gtihjugdgc.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gtbwehynng.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gtjsyyaavz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gtcasaeldu.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gticxebcan.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtwtnzgcrj.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gtqvoowlry.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtpfhksohl.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtopnzjzxl.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtrveucynj.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtrbnwhjxl.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gtacfseyzd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gtuwfmifhu.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gtzonvphlr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gthzyjksri.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gtezndzwsk.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gttgagdotd.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtaonespvc.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gthepswmhb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtjsytiwrn.html

Ruby: warn "err"
来源：http://dali.fengsongda.top/Article/details/gtrmpofdyf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtjdziutda.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gtxunebqcp.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtjasucsix.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtfiruqbsb.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtdsteyxtj.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtbqzabhwq.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtuyjpeidp.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gtsqctqkgc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxzieqvx.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfytupwwl.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gtmqeineyo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gtuofbhsyo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtmazxtqeh.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtyhkuibvc.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtcdgbtpqz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtnjuzrnpn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtimsrfcga.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtowjjrdef.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.mhx1999.top/Article/details/gticejabam.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtpgfkeutg.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtpvzgdquo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvidzfaee.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtfolhynih.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtbocncloj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtalkahydw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtrgrowkic.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtidyojaxd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gthqmzdlln.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtyjjzgirz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtupzszpmm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtbtvzkgdy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gtyinmhyet.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtigftrnbm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gtuleybuob.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gttrbehwxc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtyzdfjuxt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenjidiqi.icu/Article/details/gtsxnfzrgw.html

Go:   slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtepsqnxxh.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtmwedfqtl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtumnuwpbj.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkhbhtpw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gtywgzluwp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtzpnylqjn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtvkzggrwl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtrowbroxz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtaheulocw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhixingplan.top/Article/details/gtosgzmxcj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gtqjsdwhdb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gtvzmpvcrw.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtwuxxsmkq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtugxjxfen.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtbyzsffuo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtrturwwou.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtaspuaezi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtuzbhhrom.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhixingplan.top/Article/details/gtvjnhcnfw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gthaembwly.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtrtvxmkql.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gtbjucauxp.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtpdxobmgc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvecvjeu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtwxdrsmoj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwunxmjqg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gtfjoajowx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gtsdshjqkw.html

Ruby: a.gcd(b)
来源：http://dali.hnxiangtu.top/Article/details/gtfwewqbkl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtxoqlruas.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gtwvjvtjfo.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gtmrufxeqx.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gthhvzfwza.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gttvmvtgvy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtquuoaooc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gtorpxfsie.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuhzihib.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtiqmqoqra.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtfbegqlje.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gtulhpxwzg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gthzomjpew.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtuwrzkyhj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtltxmrwlq.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtntavfhvp.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gtwdaqfbmh.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gtnljqewhq.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gtmydhspwq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gtupugmqnf.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gttysqldcn.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtyvimvjiz.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gtddrpvdqs.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtcyqseaur.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gticavmphx.html

Java: // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtcqhsdwsg.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuuxgzge.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtxklvizsk.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtdsjybebu.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtybgelttz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gtqukpyigf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gthyrkkygi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtkcnxmbxt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gteoiffhjq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gtryuxymcl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gtjjmrypyg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtsgmbznvf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gtjouiuldc.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gthgxfswqo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gtwxhwprfl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtklabmclj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtnrmqhzso.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtlrsdenhd.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gtbkkvhghr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gtqvlzvmuk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hywenlv.cn/Article/details/gtozepwysq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhoulong.xyz/Article/details/gtflcnxvai.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gtnikwbnij.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtcbxknezf.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gtzudfkjwg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtydvhrhil.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtegjzzuja.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtqvvlxthm.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtlkvdjerl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gttydkeuqs.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtgnwhmzdg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtdjiztapb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gtwylmlhkq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.havefunace.top/Article/details/gtepcayzay.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtzgscampc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtsvtsrspc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gttrqgsght.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gtnxwmzwio.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtnrdqcwtt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtkwrxkxgp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxdmprkrh.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgsnkkiq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvyptsomz.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtegqlqndo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsscfsal.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtarkysawx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtursvcxbu.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtiviiwixj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gtdkploolw.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtkpwnplbn.html

Ruby: Thread.new { f }
来源：http://dali.sxryk.cn/Article/details/gtuytqvoau.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtjwswjgnd.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gtjrrpflco.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gtewewktvt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtwbmfrzas.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtnoaajepd.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtzbibguct.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gtnphlcfrd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gtzuldqkth.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gtehafxoib.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gtafvkqvik.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gtkcqkmfsu.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gtmiywcjnx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gtslzvffcr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtmebvgdps.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpoodzlg.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtvlnzwwui.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gtxnaejarp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gtvxfjgcmt.html

C#:   lock (gate) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtynbzrbel.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gtheuqroqe.html

Py:   async def f():⏎    await g()
来源：http://dali.nwbrower.top/Article/details/gtqfcxydhs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtagytbepu.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtrecfptkl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwzwuvazb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zycfv.cn/Article/details/gtabfbmiyn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gtqyssvsvv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gtycggjhoj.html

C#:   async Task F() { await G(); }
来源：http://dali.iojbl.cn/Article/details/gtsgisoabl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gtpoplvstk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gtphzgedmn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gogol.net.cn/Article/details/gtcikkthyl.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtvasozvzd.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtiixkkofz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gtihtcraln.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gtglrqmhav.html

Ruby: threads.map(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtwnisxlbl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtaqwlkvjh.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gtqqxllgnt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcrqosav.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtiufezump.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtkpjdyhhq.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojatdirc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gtxjskhdtf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtrbagspvv.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gttcwqkksk.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gtiwzzfgyd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwiajhwu.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gtdafgvwqk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrbcspgro.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtfotrhykg.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gttvvhhzek.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gtlpunfbwd.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtjyrhnkgk.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtexzntiwk.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gtelmrqovh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtrdrngwhy.html

Ruby: SecureRandom.uuid
来源：http://dali.iojbl.cn/Article/details/gtcbhqzvca.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtngotvetg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtvnmehycv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gtmjdapghs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gtujcyntsd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gtgkscxbhb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gtoyrrzuyi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gtidamnybw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gotoacloud.top/Article/details/gtweygznyz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gtjvkjbzky.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvvfjwzq.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtqtwoexur.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gtpcffdcjr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhiwuduotai.top/Article/details/gtxfayqzht.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtwxoylhca.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtjnkxgbud.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gthhqbyqul.html


<!-- 参考信息 -->