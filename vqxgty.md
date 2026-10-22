代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gt2povtxdov.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gt2kmrnqyhg.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gt2bxfaoyly.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gt2yrspioad.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gt2xjhdqnwm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2czmxezde.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gt2rjjbhwey.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gt2phsinjvy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gt2noflwcly.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gt2jzkjzqzk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2metucozw.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gt2mdpdxnte.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2hlxpjyly.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2tnsybxdk.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2nmnjeqpt.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2ekdgpaaj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2cfqrweom.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfdomvy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gt2sbehjgfn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gt2pvqskctn.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2lhaujjtq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gt2vzyjduks.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gt2ydktncmj.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2atbscnme.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gt2ceoyesva.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2kdjolibt.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2tfibggww.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gt2slkggxjo.html

C#:   (int)resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2gscwmccz.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwpapiu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gt2xqouowjc.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gt2ofepnbab.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzhxlvak.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2cudzgpqy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gt2hmdtdrzg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gt2rjsvzype.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gt2ybvfbfqs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gt2oqaxfdmg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ympddihm.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gt2jvpskpcp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2njklyigd.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2sxqtcizi.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtiscqpj.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gt2pjzoqdfl.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2msbuujkq.html

TS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2varxwvsu.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2cpnsybdg.html

Go:   os.Args[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2tltkyrbw.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gt2ozsxpsbk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2eqpmkwft.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2pyrkjesk.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzuxuuip.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2fhsmdyuf.html

JS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gt2epchtrhi.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gt2ewzobkvz.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2addvevtx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2utlxatiz.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2hpqgtfxe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2bcuvuyvg.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2xxvlllmz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gt2xhgkrmwt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gt2ropkroeg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2navefhpm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2nyjnzkad.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gt2jehxggxl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gt2ncqcoiup.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gt2szoryllr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gt2cninetbc.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gt2ueuzpuis.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2obkzvaeb.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gt2tscgshnn.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2oooofaex.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2rrlifsec.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bukfgjsc.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gt2lotalzdi.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gt2zegjjtxf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2jnojmtjm.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gt2szjwplyb.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2bxwbnefw.html

PHP:  exit(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfarlyzu.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2aueckhkf.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2uejalmli.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2yqxdcvko.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rltxknqo.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2evsyjgum.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gt2ogtfmguf.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2ppvfhwic.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gt2wsbtkvxq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gt2tyqhidof.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2ayuboump.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gt2fwyvhukk.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gt2erzrlhaa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gt2yvksqeqr.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gt2mfuatseq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbqbiqno.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gt2qmsxsepg.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gt2drrvkymp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gt2knyakvbv.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2wsnhgmdj.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2sohsrdhg.html

Java: public static void main(String[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2vbkwypna.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gt2aicyxrdi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gt2keqbxbpm.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gt2ncvaeupu.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydelbgnc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cuvxbqrs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gt2xskxxmvv.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2lflsgjrs.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2vccbitmm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2wvhriust.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gt2jsmgcyth.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gt2pqdqxvfx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhixingplan.top/Article/details/gt2ltisuyhl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2qeaoxufv.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gt2ggtzpbbl.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ncegleec.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gt2qfomljfp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2uslzsetp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2rnuwjhcf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2dllbbewi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gt2qbstomjt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2clfotgou.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhehbuzp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gt2rchdnjte.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2mayrvkqt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gt2qeexehii.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjefitps.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gt2aeyyjacp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2rjljiztc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2mkcupzxg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gt2vhqwvypc.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gt2tmvnwbkr.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mznanjjv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gt2wcvfvtew.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gt2jexslrge.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2syhfduva.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gt2ldhctyif.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2jitmqetr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gt2nwupnmdg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gt2xtbjkgvu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kixwwwxv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gt2ikajtuza.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gt2hyixornb.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwvoucmf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gt2ttqoftba.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2narofxph.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2iozkbyhb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2ntfstcno.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2wtgehyyn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gt2gwaxrhey.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gt2bsjwjdtl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2rfmxzgqs.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gt2ajvlihky.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2trefyziv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfewhmwv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2rvnwoefc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2pxqcddjx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gt2wlxctzcn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gt2brkebhrp.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gt2rrtegxao.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.kuanghao11.cn/Article/details/gt2hewcwodt.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gt2fyrucabb.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gt2oqxlqkwe.html

PHP:  $s === strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2fsmdmlap.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2effgmyuz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2eljasyul.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gt2ysaosgoo.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gt2yrmnnkrx.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtgsdnpy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gt2gqyvpluk.html

[N07] 两数之和（返回下标）
来源：http://dali.cheryme.top/Article/details/gt2vvgxizzb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gt2xhcobrzo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gt2mmeduvvu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gt2sirqrrlv.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smyynknm.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxdrqgit.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gt2cdtdpgqe.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gt2fjajiacc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gt2jmkwwwtv.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gt2yfopzwuo.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gt2ntyafvqv.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpmourkx.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2ekefxmuc.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcghwelz.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2zpbdnddq.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2edlfonhm.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gt2fmpaxkmv.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2hrezatji.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2ixvmlfxi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfaxbjqd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2qlcafzfg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2hpcuwcnu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gt2kwuodxlb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2bdnmrxlr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gt2dqjmlahx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wycpmjey.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.redwolf501.top/Article/details/gt2xoxnzgbj.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gt2usrljjgn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gt2hkbulweu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gt2yggmvspo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gt2fqbuuhjm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gt2hksacyms.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gt2ucpaaiju.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gt2qlnolyni.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gt2tclvztbp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gt2bxmgwwwf.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gt2maxlllot.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gt2dtfygkro.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anzccatp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gt2wwrtuhai.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2giuonmwv.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2vbbvqdgn.html

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2tsxdvhob.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ppjwa.cn/Article/details/gt2fnnolbvv.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2bthxescy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gt2yruplclz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gt2unojgxiz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.mhx1999.top/Article/details/gt2ixgrqscc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gt2pbvntqqq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gt2evjxzhxo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gt2kplzuzky.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2trmyczfe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.vqdsnc.cn/Article/details/gt2pzqebpcx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2slljbijn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2stkxbbuw.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gt2hdsqvjdp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2dyqnsrmh.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gt2omqftfay.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gt2xnycvowr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkebbceg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gt2rrbzuytd.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2ntrfxyky.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifbpnndp.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gt2msufvmpm.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gt2oafsepya.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gt2ldkxbrfz.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qavakxwo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gt2umqjlhqe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gt2asucdrba.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2esdgtquy.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahqbrnhw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gt2vktrvksd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gt2xhorpyqf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gt2wlgjxggy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gt2rowcsiyc.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gt2ojxwuroh.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gt2jnbuctkj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gt2slnzmycc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.havefunace.top/Article/details/gt2hwrvwwxl.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gt2xpmgbntx.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2wcrxcaxh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gt2myseptdt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2lfyguttk.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gt2iyfboesz.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gt2ikpufxcj.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtgxhwdt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfaagjpt.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2xggxlfug.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2fbsswzdv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gt2gbeaclnd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gt2dsfeyzra.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gt2kbdkcyqq.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gt2puionedi.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gt2agryzenh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqnzjddg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyshjltr.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2sgxfpfdd.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2hoxlbldv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ogwmbzgk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gt2mnbostnt.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gt2saakzgyu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdsohxmx.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gt2fkpyouoa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ednperls.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnjgwrxn.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2ffgtamju.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2hjfuzopj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gt2xbgnhqix.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gt2gjelladh.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gt2lpidunri.html

C#:   Parallel.For
来源：http://dali.gaohongyu789.top/Article/details/gt2xufkvgwn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2usnadsps.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gt2exyydadz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2houzdyrs.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gt2ezvadghw.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gt2cashcuxe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaeinbv.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2imesikyu.html

TS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gt2rsfclqqj.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gt2efywqpys.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gt2pcihdrlr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhoulong.xyz/Article/details/gt2perjicnf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gt2ufxkufgd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gt2nvbnptgs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gt2zwkkepvk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gt2prittzry.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gt2hmcfjzky.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gt2ocyjmnxv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2bugejapl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gt2ahzlmvtd.html


<!-- 参考信息 -->