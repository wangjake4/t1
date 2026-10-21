代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtxriulbym.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtacvumoqa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtjkvovqzn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtkrtkarlu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gtlojcmlfr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtfofixjrf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtuyeoqaoe.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gtuevyjbrv.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtycvmsqfn.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gthynrqhnf.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtaxupwtgx.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtycpbjndc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtfkfdwhym.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gtgmfcjgix.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gtdwshrdcu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtadluqjcd.html

[L07] 处理 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtxnfqkdqx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gtuiifgstx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtelomsquh.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtdjrxhyqd.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtrzycewmv.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtdbcfthae.html

Go:   resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gttmjqmcgw.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gtwbtxcuao.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtixichylt.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtsboapgpf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gtncsrzmuw.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gtdvliqnfb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtrhrhnewt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtglhnkfwg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtmjtvscgj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtviadaaim.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gtoeznhfbd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gtkpkfoobv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbphbddhc.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gttsmgtyip.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlphmekbp.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtsqgonrje.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtenitnjtt.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gtxpewczub.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtuovoyyru.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtmfyitonq.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gttprcucku.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtthutgcek.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gtdrrfbigz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtqfdmrrfv.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtrilmltdx.html

Py:   os.environ.get("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtjvutpxet.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtazvxoigh.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gthcyzkopw.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtrcizztrh.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtxofkqrze.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtqguotmxm.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtuvbnjsvt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gttrkydawc.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtbxyvaqny.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtprdqbryw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gtruoojwwm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtceaqkjsq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtvdagsccz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtweuryvgp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gtvqhtirel.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtrhbfbfvu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.haohaochexian.top/Article/details/gtlebwygsv.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtneeclefr.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gtdfpnfjgr.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gtahfcaquu.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtjxcsrknu.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtrrpehvla.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gtpgfvjjxs.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtpyprbxjt.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gttwakvuxy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivqghney.html

[M05] 设置退出码
来源：http://dali.fengsongda.top/Article/details/gtzysmyxxi.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtridasqal.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gteljccrvc.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtytmnhcev.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtdbujkzbb.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gttwskeodn.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtgwigagpg.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gtvvfwnfnh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjykzlyo.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawhrtkwn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtchvldkcv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtkwonossf.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtrqcayadw.html

TS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtkiiwqxvo.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gtdrolfhcl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gtshihpbmg.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtffptnfjh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtjzuyehps.html

[M07] 判断是否为主入口
来源：http://dali.xinyue.icu/Article/details/gtfmhpkutk.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtajpucsfx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtqglsqare.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtwboeflkh.html

TS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtkppohqlx.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gtyzmjrcnk.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtgjmmrbhy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gtpltgnxcl.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gtgjhgzjyy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnusdycp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gtcgsiqpli.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gtcsufpaxp.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtlglqrqsg.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtrlshkdqe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtabmdfhmb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtaubmcurw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gtupixogwg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudrdwina.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtiqavgczb.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtyehpgvun.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtddqtryrr.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gtzjakbnvz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtjstrvlae.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtbofbmzrd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtcozhhdku.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gthodjboif.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtlhwyeafd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtwojmrpss.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gttjyocrun.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtmztozpwt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsrjsylo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gttxdcnhos.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluhotgnu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsvmkfuq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtzmaeageu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtbxynguht.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtimggpadp.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtpdqwexss.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gtnnodvgph.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gtduhzewea.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gtgpcefdfg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtebhsohhk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtsdnfuwff.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtjgjkqlxn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gtbwwfzkeq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gthuevgrqr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gtqzrppkag.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gtzfscczmd.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtqyiaarmx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtgmwilchy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtvbmartxt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtmnaugbfq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtfhyfxbms.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gtuebglcxd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gtmjpipfhh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtklhvqgan.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtpbrxhryb.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gtlrvjuoko.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtzxtqsgkm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtorabxhyy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrslbefpm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtnrqfavmk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gtqbcjjkjg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gteuxytnbf.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtualevkni.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gtdmzfgwzx.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gtygqgduwq.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtpqhrxxrd.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtwoeogsag.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtawchrnxb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtaefbvzog.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gtkulmsabk.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtmgietpii.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtgjsdsjel.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtdidvueit.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtnwhzjinr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtbzimlmfz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtseiiiofp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtswxlbrsk.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gtheounkmp.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gtxhcrmyez.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gtihrlrlnz.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gtljapmggx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtrichjfwm.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gtnvxlrgcl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtbwhduuah.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gticyovjus.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gthkrttzot.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtrblnuaud.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtsbdglnud.html

Go:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtxatndmwo.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtxolxownz.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtzbodelzq.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gttcrywsay.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gteywnpmsn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gthjqobeki.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtcuzmsafi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gtllupsbeb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtooibqdea.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gteguhnhgp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtijoorfel.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtvuegujtp.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gtqlcomplg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtnimnmddf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gtcpqwxgzs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gtuqcczufh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gtltywievl.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gtmlnvdlvm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtaccbgzno.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gthnhtjazw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gtmxyguxsj.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gtejerrkql.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtriguuqth.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtksetkfym.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtcrblkete.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtidrcrdrq.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtnfuwhnut.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtspdvmdic.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtxrplastm.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtiokfsyjv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cdnleiting.top/Article/details/gtzrgjucuj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjwmtgax.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gtscgqvxyz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtevmzyrro.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtpytoxpik.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtunjdtkvf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtwsrckmfv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cashguo.top/Article/details/gtroiaytrl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtcntqfdkk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnesmcgli.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtaacvmmad.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtegkaknkr.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gtdyemzdxl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtnlecsjjz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gtamufexal.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gtsgrwhjeo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtljavjxnn.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gtduempdjc.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gtdrcfjfit.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gtevqokgtq.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gtflbykfdq.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gtgdkfgtiv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtpcbsasdr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtuanjrdet.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtoeqvkjnm.html

TS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtxjnwekre.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sweek.top/Article/details/gtnluwxijn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtqglutoff.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tianlin.xyz/Article/details/gtolhcmfzy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gtzmdcpqon.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtnduojkzk.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gtgzephhoa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gtdakierfw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yonumen.top/Article/details/gtbvryrpvc.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtpdwpgpri.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtefubbhzp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtgcadloso.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gteltvruvn.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtqqurwhke.html

[O04] 定义异步函数并等待
来源：http://dali.hywenlv.cn/Article/details/gthcnuaoag.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtiwesdmem.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gttdvbmsrk.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtddwpmahl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtalvqouif.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtaocmybvc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtqcoqeaqd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtebyfkphh.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gtxxzvjgue.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gtvsfjxitt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gthawaanck.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gtqsnydoqk.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtusehgpmo.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtnzoavvgp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtgmugaiue.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtuaumvetn.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuzrnzcf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gtwebjdqah.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtdvvyuzbg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ydzc1.top/Article/details/gteercmgmr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gtqdulbush.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtmoensaxe.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtufxocdno.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtvtzsseyg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvtlwflp.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gtftidafwh.html

C#:   Parallel.For
来源：http://dali.9152youxi.cn/Article/details/gtumkpvhgo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtopajlabo.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtjvxluzoc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtumncduai.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gtqvvucwtl.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gtwbawglnk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gtawbdcsdu.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtulxenwsc.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtmezylspb.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gtjeneubfq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtpeeihhgv.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gtrtggvmtw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gtzazmgqxx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gtguqmuceo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gtbzbeciwc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gthowksxow.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtwjmvtdfp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gtmdjgpzzf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gtyiunrnfm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gtmlzlhdeb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tianlin.xyz/Article/details/gtncpjdekk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gthwedlpag.html

[P03] 生成短随机字符串
来源：http://dali.pycfn.com/Article/details/gttopyduum.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtrgqobfbq.html


<!-- 参考信息 -->