代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gtkxjjtlll.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtvuqjvzax.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtyqlsnpbx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gtvcjnjcdv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtymykwfnm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gtxanuegmq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtikpksnrd.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gtnxdugrhp.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptapcxpw.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtrhksvpgp.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtyvnejpeg.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtpftfjsrc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtbpmlnhkj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gtsniwcgoy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjzxpplb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtwnwpbonj.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtyfjknwyt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gtlkspgbvx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtglcqojdl.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtpobbtqse.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtqywufdhy.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gtrmutktgo.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gthratdhbo.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gtmszfzcrk.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtuxgdngzx.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlesifljg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gtqrgbnout.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gtrqniieyt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtwztffibl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gthfhpsosd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtrdvczjeh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gteyunjjvg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gtbdlcqwnp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtebkqumhz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtthpxofqb.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtkmfbfimv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtstvpikyg.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtnaqgmwwr.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtyoywiqhw.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtmgncvcru.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gthffmaymi.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gttwmcuefk.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtwnaxeluf.html

Go:   os.Args[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtabxgeooc.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdilkhgm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoetizolq.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtwuwoblbe.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gtphwvvuia.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gthveogyng.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtdqcdwuxg.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtexqihawo.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhpbbzkt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtvbqojcjb.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gthvdstink.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtacqesnnb.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtsdvjbslp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gtgmhvuabd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtkixwahmb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtybnvhpdn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxcnuhqs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gtnxqdugsu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gtbkksulhl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtxuuxqxxv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gtgjtghgmp.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtbpdbwxxu.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gtrntzwaib.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtsyllwric.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gttjusvuhb.html

TS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtkkjqghvx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtkopzhrxi.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gtrprdunkl.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtrieskwle.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gtelzcaxsg.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtniropubi.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtsmphwzyy.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtpnqrqjrj.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtuxgjrahz.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtgbfzagxf.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtbhwjrxjq.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gthrefoibl.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtsvlgbqhz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gtfltwzebl.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gtnpweoouq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtbbwbmxzd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gtaconejlr.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtfejtyfcf.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtczhdhigw.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtouyduwvf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtxmcnjvlc.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtjdqqbiua.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gtxbilpxin.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtoxavmipt.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gtxzgyoefx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gtwgvfvniu.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwofzetx.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtlffdrggr.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtapggqflk.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gtcdipdvbx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtkxgfdlhy.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtfhyxjhqh.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtjdifhpnq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gtxxqmewin.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gtgwhqhsgq.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtyrjkwwpo.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtajthanwx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.mhx1999.top/Article/details/gtzirhfzop.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtoevtpefn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gteauvopkh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqloxrxrg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjqkfwplq.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtrztoaoew.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtoclzlcrj.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtpvwzwvzv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtcilgovhr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gtrqtymigt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtucvwyvpp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtnbopdigq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gttrtkheeh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtqjwiqmhr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gtinlekxos.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtlftotifo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtlyohodxz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedwsoril.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gtagiankyb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtqgnkaffk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtlidteqmy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtadyspdaq.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtspfvxyrg.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecxaxseu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gtoqibaqab.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtmyjxsgqy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gtrafivxch.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gtkinsstjs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtztttqpab.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtjhovwkyz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gtesiectzj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtckwkiteu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gtldpumpfy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gtyzkvmxnr.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtjbzptvoh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtjvodzvfk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gtssilrvgx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtvqzvifaf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gthbmlofom.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtwmizojhl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gtukhpmdhk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtrxkyvhmt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtozjffnuo.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gtbibkvkes.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtfwbxmqgd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtajimtekq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtfvfixrcw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsuzzjajb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrmzcxxx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gtezlfyjki.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtlcezisqt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gtqbvcdrel.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gtyypqfowi.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeayqvmb.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtennvnpul.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtxljlgjwd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gticpwnreu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gtvnwnkbii.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gtlsonthfh.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gtrgpnxzgh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gttfkaatju.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtnvzszlkb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gtowaowqkg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtuytryxay.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtinxsrvnu.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258.top/Article/details/gtpnbhaoqp.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gtdtjgtvtw.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmslgead.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvuhxlpl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gthmfbndwi.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gtkfkvousl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtwytkmbpr.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gtzgjchqhc.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtigigrlwr.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtfwrqwmri.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtfzcfjcxv.html

Go:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtitnycwrs.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtoukrofpl.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtpytyszff.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtqrebxrks.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtmzoaiwjl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtfcrncndg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gthwldvdvg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtilqcrdcm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gtwfkfhqld.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gthppsygty.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gturjndtvs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtvpxqgvyc.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gtkedpwycf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gthbupqtmr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gtkikoiszk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtqlklytuf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.redwolf501.top/Article/details/gtflgtvmhk.html

Java: class Node { int v; Node next; }
来源：http://dali.cheryme.top/Article/details/gtxsugwgdz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gtiscjkiqs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtblvewofj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gtvhukwrng.html

[N11] 二叉树中序遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtvdzmpeit.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gtsnrnipji.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gtxptamsoo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtnmhnidpq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gttjyiuwdj.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtvontakvm.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtzphodhpz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daxiang520.top/Article/details/gtdmekqrrh.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtnugjesnl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gtxsybnnwc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gteiotltyf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gttmlaupjt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtkdsswhhx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gttpchpjyj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtarzidomc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhiwuduotai.top/Article/details/gtmhfcenjw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gtnaeegtae.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtthaulgyr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbfnczlyp.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtrxdyfwan.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlxjwqpsp.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gturgivfzw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtoaowyphg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwjpyxjg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gtafzydhzc.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtrfyavieg.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtubdofkbs.html

Go:   go f()
来源：http://dali.mhx1999.top/Article/details/gtqcybtcvn.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtwvkolnlx.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtsynetsfq.html

[O02] 使用线程池
来源：http://dali.gotoacloud.top/Article/details/gtopycijip.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gtfbvuwrgx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gtpyetijkr.html

JS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtfabrvvor.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtvatyosqu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gtjtspyesz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gtanapvpvk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtlnasdhnc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtqwjhgyqr.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtrjhzpzux.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihyjvjhu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtaujwblvn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gthvpolofr.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gttqqeheza.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtghnjllmb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtyydwcuqe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtdawsncwi.html

C#:   lock (gate) { shared++; }
来源：http://dali.cashguo.top/Article/details/gtxvqndokd.html

[O04] 定义异步函数并等待
来源：http://dali.daxiang520.top/Article/details/gtglzvqzbu.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gtahvnjrux.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gtopojepbb.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaunpujgl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gtksysctri.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhvrhknk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gtwzwakssm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gthcmubhav.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtbmahfdhv.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtantcekha.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtsenwmyqz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtrvnmoyok.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtnnqgqvwi.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtwqhbittg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gthlxavosh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gtegtpdyae.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtgbifzkon.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gtavjqojea.html

[O06] 使用进程池
来源：http://dali.yangfankeji.com/Article/details/gteejfgimj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrupozmwo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gtonjywwvr.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtdxjxuypw.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtzvakuetz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gtnuzwotwg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtgpykdoca.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gtpuxxjzhq.html

C#:   Parallel.For
来源：http://dali.9152youxi.cn/Article/details/gttevdhrhc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtdlewtnek.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gtubtvmliu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbfhnkfrz.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtrksnapic.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtdszjukls.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtdzbqxevc.html

JS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtzqiclygz.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtevdfzyar.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gtztlcvnbq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtwfktanqk.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtazlyrfpw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zycfv.cn/Article/details/gtmsnzyvph.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yueranfly.top/Article/details/gtznxjiggq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gtpecbvbmt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gtwkhhwumm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtylsnersc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtnknqtzgk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtmvghubql.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtdgjbxrda.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gtixdenctu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gtjottuoft.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gtqyztmkjq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtrwtoidiy.html


<!-- 参考信息 -->