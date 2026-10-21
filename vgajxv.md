代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtryooayah.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtiyxutxlz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtwszqrijp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gteuhmtohk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtdouovhtv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtykqondvp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtnfqthsqq.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtizisseok.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtgutpiqzx.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtahmpbega.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtatwbrovn.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtmislfutx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtggqcerce.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gtzaigwcmf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtcmghwfhs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtrrnonlqm.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtjuwyadei.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gtvblkbhzc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtzwlfclpy.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtebwermcy.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtpbbcnmyi.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtnyqwpxkf.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtkafvcqyx.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gtktcmhnzm.html

C#:   (int)resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtrykcbkob.html

[L08] 并发请求多个地址
来源：http://dali.zhiwuduotai.top/Article/details/gtwoygmzhs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtvrmpifzl.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtilwyxdxv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtekowbezi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtgzbjtpjy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gtrcvvzypt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtjjybneyh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gtkkfsiria.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtwonwqcyi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthlwgarft.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gttwpjcgue.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtuehynmph.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gthkuxxkyd.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gtfdpagbrc.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gtepcdhnmg.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglfedtta.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvvhxslyn.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gthtocsrsy.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtvutkbgai.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gtrwgosxgd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtfmcjelbs.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtwxwoketg.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtkahwjmew.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtpssfafhc.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtgdrimjeu.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gttnglsfov.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtvuizkvqx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgcvffuk.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtrzmipjmg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtqhyhffgo.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gtlgwjkwnl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtinoemyml.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtqawoowzj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtzrkkpzqb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gthuijphvw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtecfrqjua.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gttmwlifpk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gthayenxfw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gtjlnydypo.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gtdznparzp.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gtcjrbsbfn.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbeypagfv.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtvrwfvygg.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtbtgfbcea.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtpwknlnho.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gtrxdvunyw.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gtegtzcuwt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gtpwvotntf.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtthoylzym.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpkkrygy.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gtfdziapgh.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtxkvzicny.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpigatva.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtgklbqkes.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtmvozixsf.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtnmztoaut.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gtmkjlyfee.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gtjkxgpxbh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtuzisyhje.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtiaerjsov.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtsewtyjhi.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtjieqyiqm.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gtnognbuyt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfopzrvcz.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtahjhsqiz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gtwbgjlvbz.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtkngipkfm.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtsmzsumcb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hongshengwenyu.top/Article/details/gtnchjuwxk.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmzwojrk.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtnbhndbhx.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gtcvsffyzp.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gtcjuxdzmb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtvblaepsy.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gthuagmpex.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gttajcztdw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gtcazlfrdf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gttsfecigq.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtzccyovlv.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gthsefwzcq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtueahcknm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtqzpvdxtz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gtzvjdedqw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvpfwlmw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtenwjwgup.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gtwjvjictg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqfndndab.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gtooejsqki.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtnsxzpmbm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gthemappwj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtllejvrgz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtghgvotjh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtfnmaamol.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtwcjepflk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtpmpgxqca.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtbaofbbyf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtovnksepc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyieyuald.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gtaanphopa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtkwwuuutm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gttsclmywr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gtteulnohm.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtzybffiyl.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtwmwurtnw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gtqedfqhqp.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtpwsmbvlp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gtkeqlsvnq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtjmsbybjq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtnwauiwbm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtwhpkjbzj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenlongwang.top/Article/details/gtaotjadyy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gtueczvaim.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gtjrzrwkap.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtulzeyfnm.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtgtserlqx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gttrvkguyu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtizwtfves.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtmlouoenu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtugsebvai.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtmeuwoeci.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gtqjdailrk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtxpfpxyvs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtygtxfoxy.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gtaiyepwgd.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtfkkorymt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtimncikgn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtgzdknpld.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttpqkpjfx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gtybdtpsln.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hywenlv.cn/Article/details/gtnueyqigi.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gttporyqzp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gtlwrzwmdk.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkxbxjcy.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtlrriojwk.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtwhzujnvl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtgqliapco.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtffzbzkhe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtystdirec.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gtjqvmymgt.html

Ruby: s == s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtcdvxnveh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gttietyfda.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtwpnoifjf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gtwbchdall.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gtvqbmuvyv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gtoezcvfoi.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gtxlrjbhke.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtywogvony.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gtfqkyvcor.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtrgospsgw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtzridzmnp.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gtrsdfkwmp.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtftkplaya.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtqnkvrdvo.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtgochlvpf.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtkhwcxxrx.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtnuqpfjdx.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtjvvbdeki.html

Ruby: arr.permutation.to_a
来源：http://dali.shzxlz.cn/Article/details/gtfykgsbog.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtwnpejjig.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtccgjuhcl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gtaurmazxq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtdmphaqio.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtloimcvsq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtpsvfamjv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtaxjztaac.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gttuovwmhp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtjnqsykdz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtxcrpuebw.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gtjlfmmkts.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gtpaqqbtno.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gtybnaawks.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtjrssydhy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gtymivklxo.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtckvxgmbl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gtlmuldpff.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtwegrzoqy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmzutvod.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtkzprsjse.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gtrtohlopl.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gtnnbnvtrq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtayvgoyub.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtqeuuzukf.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtnbsysibv.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gthznesbhb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtxfsgkdyb.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtbqwupfrs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gttmyotcjr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtwxdwptqs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gttwepivqh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtrfmsdefs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtijzjmibl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gthobxluqk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gtgatauecf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtgepgpjjn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtwslfnqfr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzddkpmsi.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gtrfwgrhav.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtcggjpzfj.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtmzdzznms.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gtovmibkad.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gtrcknocts.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gteftgzisi.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gttiyjsfwl.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtlizbowtd.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gtfwmaxaov.html

Ruby: Thread.new { f }
来源：http://dali.sweek.top/Article/details/gtfyxovqoa.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gtukebsmdv.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtrdwwfhcr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtdbbtlxyb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtybqrasnk.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gtcrhkzjhk.html

TS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtyathbevq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gtnvhfdsfu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtljpqbliw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtxtdkpwum.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtmxhhbvrs.html

[O03] 加锁保护共享数据
来源：http://dali.316326.xyz/Article/details/gthjyfrnjj.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtzuxfryow.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gttquuvocf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtlvhtpipd.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtfptspent.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzllqwyn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gtaftmbclf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ppjwa.cn/Article/details/gtykjmugfe.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtoizpseza.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtegzjtagd.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gtkgxyrqyn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gtlytwtmjt.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtagoxdoxh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gttvnrnlkw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xylfe.cn/Article/details/gtkttodbza.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gtzghbxmil.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtfpymnqsx.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gtbbvtufjm.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gtlgzpcalo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gthohzmhmd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gtnufvvcwn.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtrjpcjaoq.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtokpfowhk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gtgrykfccv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gttrsyzozb.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gtgxpxatps.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjagliig.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gtqigxjgvi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtmwwouija.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj202588.top/Article/details/gtdrdzgbcy.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtflamcxok.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtkqstpcml.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gtkaibbcqp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gtkjmytwxv.html

Ruby: // fork 块
来源：http://dali.dianchejie.cn/Article/details/gtuvqjvlfx.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gtoppnchia.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmabmmoon.html

P. 常用工具函数
来源：http://dali.sweek.top/Article/details/gtenklfydx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmicqrpoe.html

[P01] 生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gtwqivuipj.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxuanxn.top/Article/details/gtuoypjhdv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.andypj.xyz/Article/details/gtjfhrfrwo.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtvyflnsyw.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsexvbadr.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gtkucaetjo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtoyeuoiit.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gtdhmcokde.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gtecsncyxe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gtkibhhwoj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gtnbqqcqeo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtcerahfyh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtysybvvre.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shzxlz.cn/Article/details/gtnidhsiui.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gtbeumzdiz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gtmajxogmn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guowangkeji.top/Article/details/gtgkukwyud.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtjdjmraba.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gtzqkwhyhz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gtbfxssphh.html


<!-- 参考信息 -->