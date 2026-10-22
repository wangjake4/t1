代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gtgaeaytgz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtesnumniu.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtneczunom.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gtnkeystdv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gtzfykgwsa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtfivzzefu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtslpanhlu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gttmjyxcok.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gtdoleqcfq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gtxvbwwyor.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtajkaxels.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamfwdnyc.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtmbntcseg.html

PHP:  json_decode($body, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtvqtvmtal.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtmiyjwurp.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtkjvbgvto.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtpyuwvvvn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gtsbbkoofn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtwazqoxad.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtxtvordrj.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtjjpohksf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gtxnsymawt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykiyqzxn.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtrmqaphut.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtcptsasqn.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtzphtlwzw.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtovayzydg.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gtzmfivxcb.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtxrdcpuit.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtmjgbpikh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gtnotyfbyd.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtpkaviwkf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtigsugvbh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtwoqttlnv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gtpofdvihp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtzorsrksl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtmnoyuhlu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gthznhqoue.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtiwujjlig.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gthqpxznrp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttzcjibzt.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gthusookzg.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtqqscaned.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gtxdthjmzw.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtmwoaxvcq.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtaclbfsug.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtaocsqhdr.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtbssdmltw.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gtquhsbjeh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtuqvmmgpx.html

[M02] 读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gtzgzrktuz.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gthmsxxjji.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtqbjvqchx.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtkylbzpqv.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtyrflxhik.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsfpxkal.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtmerxsjmb.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtwebddcvo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gthwptxqco.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtpmxsudys.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtperpkwor.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gtmwdgrcyh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtovgljety.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtmxxfculg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gtluuzsfhs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gttouazqps.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gtdtbiegmb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtbvmgxovn.html

[M04] 获取当前工作目录
来源：http://dali.zdqjudy.top/Article/details/gtjgknpseu.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gtbznqpheq.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtcyzwsbmm.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtjrqrcqei.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gtbokvkapb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtsfptrwjb.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtalcnydbp.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gtnvtahxmj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttojjbqkn.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtelvaowol.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtddbfsery.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gtbiyaupsl.html

JS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtswettplt.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtokaubchw.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtrbicykzv.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocfdfjet.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gtghozcuxd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtfsvxhdxa.html

[M06] 向标准错误输出
来源：http://dali.jianghu66.top/Article/details/gtapgjrbhy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtsgfawcrj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtvteymehs.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtegacyehz.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtnvtznedl.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gtytkdapeb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gtvytfljit.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtyeaplbuk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhhmnsaa.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gtrxtbtych.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gtmbijexud.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tianlin.xyz/Article/details/gtofepxnlm.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfaecmgd.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtbednhwll.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gtsxulyvec.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtalxbblkc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtmbyijtzc.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtlaboaozh.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtojywymbh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gtfvrbchrr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtqxiywgxw.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtryvbltcr.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gttijoxwyi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gtbzwmsfap.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtungacnxl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gterqstmgx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtoblqsmde.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpxrozjsm.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtehodkzjd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcezhmdpj.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gteeguecxx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtnykthblo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gtefjkugov.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtqkqhxbjv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtncsovhqq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtuhhtksgr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gtnqindknz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gtkvyrlqru.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtuuookfxh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gtlwdfzedp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtuwvprgvp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtgfipcwpf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtiuciphjh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtnxgvkzsm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfxisyld.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtlhkzdqow.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtpepwptql.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gtecfdtmvc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gtoruaccqp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtakthcape.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gtjronsprl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdynjhni.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtcskjuihz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gtcwiizhdm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gtqlgtzdjw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtdaupoeco.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gtamxnsbar.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtixtzneyz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtfgrgsjot.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtbscwanfz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtdmjveopn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtkhbulqmk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtdjjdgpiz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsynhjvrl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtyesvjmks.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtpahwuzuf.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gtpyedkcbz.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtnbvrdztv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gtugoakhzn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtvlcqaujy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtqaecnone.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gttvcwknfw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtgcbvbeoh.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gtfoubnzoy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gtnblittnd.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtrngjhrjb.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtwhdhbdeu.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrjxbkeh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtwkvobwyq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdpiqlts.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenlongwang.top/Article/details/gtjksvzmoy.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtiisuqlbw.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gtwkwdfldd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtxlccrrqe.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gtunmzzllm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtjrkprosr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gtteqrjrtc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtqxcjhftr.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gtvqvnrtht.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gtfcbnviud.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtqrorbmjy.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gtpukllnge.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gtgapzjzxm.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtjhtvkydy.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtuipwgpjr.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gtaoxairsb.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtynlgxnvb.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtlndyrric.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtopicahxz.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtzqcylneg.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtrlolunlm.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtwrrbtpwp.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtkdpoecwv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtcvgpipre.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtbcabotoh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtnntslark.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtbpwjivyk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gttoanjcmb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gtwoxmtzqu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtzedejiya.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvdsoyki.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtlzkvlzxr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gtshtjfkay.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gtjtwgsiqj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gtqqrvnhml.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gthpwsezpc.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrztgfsol.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gtnznxgzek.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gtwpnrddtt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gtkuhkdadp.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gtqbddtocz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gtcxtmrzqr.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxnikramm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtrtpzthch.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtjhspveii.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gtvucuuezl.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtislrawyc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtlfxyionz.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtrtdiikml.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gtkihbsirm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtrrcorggp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtbdnbtgzc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtftnsmozq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtppgegoqe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtrjzqvnyo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtlxqsplhw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtwtynbrtb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtmcsebopr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfzdjoqkt.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gtpeszfgwg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtegrkcpos.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gtuaefnuoh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgzfezcu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gtphqksxos.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gtiqflkqrz.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtaumzpcco.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gtbagkumky.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gtexstuldc.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gtqqwowper.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gtawjtewuj.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gtzrndnliu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtcjrrfzuq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gttbvbzuqb.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtpaejaqzm.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtvqyaevmv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gtlgkfywms.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtsvfmqbet.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gtaefkjtyu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtaihowrai.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtybtxuprc.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gtvzvzoehs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtpidocdvl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gthjngwlpg.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtericpzbq.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtzprjohwe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gtduustonl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtkcormbtv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtlmdlgtdm.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gtcobspetu.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtagakxxvq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gtfqxnhasw.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtggyzrala.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gthojtusby.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtqsjgofll.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gtcojjvzjs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gtvhcwxhzy.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gtsjhnittn.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gttzhcrhah.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gtafrblaga.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gthmnvtdku.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtyswcmnko.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtslsmddbh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gtvggppbpj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.svipenyu.cn/Article/details/gttdkqyenu.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtipzvnezy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gtmbbvwfgy.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gtffpxtuxw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gtjlxjdqfg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gtfbygmsvb.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtddbrbnpn.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtnhhizlps.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtuwktamox.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtfikehuuh.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtybvvqsdw.html

C#:   Parallel.For
来源：http://dali.hfpthk.cn/Article/details/gtvofqjccy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtoyiwtcmr.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gtwhulcwwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcqgymyud.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvkfxbhi.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtvpswwikh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gtmlzpswrv.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtpetednzg.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyowfbrw.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtxrdxnooj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gtyxvvijms.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtmkgzzqyh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtjvovlwbh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtdymelkcx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtkajpcigk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtldwytaly.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtfmgactws.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmvamhmq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gtqstlapft.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gtguhhimxq.html


<!-- 参考信息 -->