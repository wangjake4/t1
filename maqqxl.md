代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnunkzlv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gteehvxemf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gteevayqku.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwmruxye.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwojtzdsh.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gtgjdvsqhx.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtlvdawmzi.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtkqwjoeev.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtdmksewdp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtrfhfqceh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sxryk.cn/Article/details/gtbhkseqis.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtzpajgtvu.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtnekknlrc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gtjlexfzbs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gtdchmlddt.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtmyktymgl.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtrgtrdcdo.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfodkdrx.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtdisrniyc.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrojclty.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtdvesgmqp.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtrxtbmvyp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtqefmwejz.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtdesrasrg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtautqvvug.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtbvufpzzo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtmhyplwnv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtbajfzhwu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtpcoiinas.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gteadvnjdi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtenwymwjp.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtkvfzvcvv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtiirwmtfb.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtbxfpqgsw.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gtbubbtmbv.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtjbiwynar.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtjyzxphkk.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gthhesabpb.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtmrddynvb.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gtxzxghibk.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtmqsfojrr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtpscdndml.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gteyisormn.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtprbixezm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtgxadixpn.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtqmdjyvku.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtgiwdpmts.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtgwymfpvd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.havefunace.top/Article/details/gtplpyaytk.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtboldvbis.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtxvuezlrx.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtrlniszvr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gteavrxlnw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtbflwlkwg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtegpuwthm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtggglpkxo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtyuligxwb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gttomigoww.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gtldhsluyh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gtamngpdar.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtpwenbddc.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gtbvqbxpah.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gtmzdjuvqq.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtiehchxqm.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtwcgxutkz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtpwlsahpo.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtilpzgzpp.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtzrydvsao.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqxjgvzj.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtrjuuzahd.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtinlprsgf.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtaqdahqsc.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtodsexala.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtzwuseqjq.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtyabubsqn.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtbvbxmwjk.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gtamtlezlg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtcfxmojll.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtfxwwqias.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtmeicwyvy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gtaxjxkjje.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtbrvrgyqv.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtjemewxdt.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtrwrmhglo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gtlwjtmvqj.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtfjaxuvtw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxeyqzyg.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtpuebnqck.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gtrrubvdte.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtakoduygr.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtrlrwmkbm.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtzcqktcia.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gtufiqkddz.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtxozpxebo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaodwngdq.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghdmivki.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gtxgnamdoo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gtddfbgyci.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtepsfjikk.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtqzvnyijm.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtrxvcjino.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtdkavyhcq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gtvqikgxqq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gttjvofamt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtbmfkiywc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthdmfydbf.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gtjnlomwce.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtuvjyyhks.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnaqujit.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtugmgxqgr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtnkwvjdno.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtzrsyqzzr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gthfinsatp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtkhbruwec.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gthexhvxwj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gtjhxvhumg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtsrhheoll.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gtwqbnpzfe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtefooocgw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gthgeuwiar.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtjnynsubl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtvnicdgzu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gtvxaajtod.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtxtvtbxpl.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtfxvigwno.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtioogzabv.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gteehblnzo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gtcvshscic.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtuqdstdbz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtmgphuoqk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtbbfusuqc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gtifyjoend.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gtuwgvpcel.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gtdnileuec.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtbymeinuq.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gtqutfjrpj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtpyrohnsb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtsvmfktec.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtfosmdxss.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtdunfxwom.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gtwchvvepb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtihjwnytb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtmsoplcpz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtytjgmncn.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gtijejjdyc.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzurkyflb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtpakygkrj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtenjrxhgl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxmejegv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gtcxlrucxw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtlmstpwbk.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtnizowbpo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gtwnzhzgfi.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gtxzcjbqsz.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtxgsyuhaw.html

PHP:  $s === strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtouvepbhp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtpkodmvhy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtqtmtgjem.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.bjfxy.top/Article/details/gtvcczozef.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gtsqzmiktl.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gtqlxexxff.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtetogxwbw.html

[N07] 两数之和（返回下标）
来源：http://dali.ybcxt.top/Article/details/gtuchxygar.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtmxrtcksc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gtdqgqymjc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gtqvrvxete.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gtlmrntmmg.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gtdcupqppf.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtvqbcwsor.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gteyqdagmt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gtvlmhrqfy.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gtppldqjbj.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gttubfebri.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gtswwuvrtf.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtndpmrfef.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtxqglxlqi.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtnpykwhgb.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtwxakijir.html

Ruby: arr.permutation.to_a
来源：http://dali.guowangkeji.top/Article/details/gtbmkcebaq.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtakocjdwi.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gtmaecbjcj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtutqqcqnf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtmvnonvvy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtbqombycz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtgcksllve.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtbbfgapkz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtcmdanqyo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtkdceicrb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtzzetyjqw.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gtyyqszony.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gtqehkfbzu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtvnarvjjd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gthuzstdnr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gtpfrttbvn.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gtccaogtan.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtidmuexkl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gtddycbwdg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnqqflxhy.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtunfarxwt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gtefqcmlvw.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gtjibmhwgj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtikurykxf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtlcwvphjn.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtpjzycrxf.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gthulsxmsi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gtsznyilfq.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtupymqrbq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtztwwtdrz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtksolyjlx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gtaamlzkmm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtcpikfzgo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtdjkbdukq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gthhusaijg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.bjfxy.top/Article/details/gtiamvhkpg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gtkfzwyefb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtnuclvdzd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtvypvllms.html

O. 并发与异步
来源：http://dali.meibo888.top/Article/details/gtjwvzbkto.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtumfpbxrx.html

[O01] 启动一个线程
来源：http://dali.xuetiantiany.cn/Article/details/gtduurmibw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cucudq.cn/Article/details/gtfybkgysa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gtteiqxdgs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtrtggsqtq.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtwmyqhtjf.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtokrngmnx.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtgfvrsojd.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gtqnxkyhom.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gttracurha.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtajoenatv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gtkupbqtdr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gtrfknzdig.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtsabzhehz.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtacyyvdwz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gtlfhgpwtf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtwnsmysxr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gtfyxbnbnh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gtvwpymckp.html

[O03] 加锁保护共享数据
来源：http://dali.hywenlv.cn/Article/details/gtvzrjnqth.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gtqeukrqny.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gtfxbhpbuz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtpnagadnk.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtlvonmgop.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtcwgsibvx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gtbblzqggs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hysaishi.cn/Article/details/gtkgqybmxr.html

C#:   lock (gate) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtwrlqeppk.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtomtucplb.html

Py:   async def f():⏎    await g()
来源：http://dali.redwolf501.top/Article/details/gtplzngyar.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sysykeji.top/Article/details/gtiuvbrkki.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtfrbtbrey.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtcyudfuzd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gttfwbavcd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gtlkvyhsud.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gtxzunkczh.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gtfwcxrkbd.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtkbclqgup.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsgpbefh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gtxiinjmcy.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtryvftiwb.html

TS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gteafwjllr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtzfnbceft.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gtdbgpjhcp.html

Ruby: threads.map(&:join)
来源：http://dali.shuidangran.top/Article/details/gtpxvfcezb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtapmivgnc.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gtmnttamet.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gtxnzvkdat.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gtglirkfqd.html

JS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtnwumuoxb.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtrluhnidl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gtywpxzlja.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpfiwftz.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtgcmidfsa.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gttlzezdtp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtelkmhycm.html

P. 常用工具函数
来源：http://dali.cdnleiting.top/Article/details/gtqprhuykl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvbraooeh.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtfsutimys.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gtnajfjpan.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gtykvnuamm.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtceifvjnj.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtxlnkquaj.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtcajmkxwu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.c1oappe.top/Article/details/gtettpczux.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gtzhdcjhbx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gtsiwxathc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aizwys.cn/Article/details/gtxnzedngc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtfkwdtdxy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtvjgrmveo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gtkraltadm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258888.top/Article/details/gtywjygjrw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxroxslx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtwijjmena.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtdbiohaln.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.smart0.xyz/Article/details/gtflgoaipc.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gtjgqnnnnh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gtvdgkfcok.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yvedp.cn/Article/details/gtpmhwwlcf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtshcgbjmd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxitzqiaf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gtivljzriw.html


<!-- 参考信息 -->