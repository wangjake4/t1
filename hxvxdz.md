代发 wailian999

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gtgvtiunss.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gtzzdqwedw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtqldatica.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsqhupfqn.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtufdshuya.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtnlqaikqb.html

[L01] 发送 GET 请求
来源：http://dali.guowangkeji.top/Article/details/gtaqdoqymd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtiujmrxfl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gthdefplww.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtseaftpdf.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gttranqtwi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gtwhnjafkw.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtomiitzer.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gtjlxpgekm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gtxhlbdevq.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtspzhndyt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gtnalmkvlb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gtpltpeqaa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtleyykhpr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtrcqnacun.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gtepltwtyh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gtkqnjieqf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtjhvlmprv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtuvjenazb.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtcmobbwvf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtbydhigir.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuanzhike.top/Article/details/gtfjybdstj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtmwzrgxri.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gteyzfnyns.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gtutzsiutj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtpebmjibp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtkomqihyh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtbbursqyg.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtksuwtaxg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gtsxwcmjdi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gtoitnvpsn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtqolftcse.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtcntuolvu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtwrevtusb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gtxsuzehga.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtbmmcooct.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gtxaphglek.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gtlrcvhdya.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gtugqpezji.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gtiycayvjt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtrsaokvdu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtigjuipiz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gtmatslqgc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gtevcveevu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtdzngkkyv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtgdanjess.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtsbruyjxp.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtdegskwor.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqkhxcqs.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtmksnjmas.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtvzqyudhz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtauhylspb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gzhubu.top/Article/details/gtcfleawet.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtnqysjtwd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gtqplvpwes.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gthiughcfv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gtuufmfixn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtzqckgzyl.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtcopqbcce.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtdbjfanms.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzovzqsof.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gttsoevdqc.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtqzeshqek.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtfpvfmgzz.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtckglprfi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtkcmfeden.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gtpwgsieco.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtazwurxzt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtlwbuqaux.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gtwtgctnyp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gtigspfmvp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gthntrjqwk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtopigzbym.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtaidghttr.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtamlxkpnz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtugftbsnx.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtonsvabsv.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtweibiysb.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gtfmgbburl.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gttmuclqqa.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtxyecbbbr.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlieqwxph.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtslpqryid.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtaeeydfku.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtcxlirccj.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtzuaewocs.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtwsmpacnd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtmshsopwv.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtzjchxxba.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtdgmlqncf.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gthlaouoqk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtptopuxel.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtrutuszlg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gtdqnbpuae.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtmyifpaof.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtnbtbjvxp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gtywedfgrx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtwbyfsiso.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtxyhliqvf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtxfviprfh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gtjnystdto.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtrbxponmv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtviyrtbdw.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gtnfmtseii.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gtqbnhqknj.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gtmupekqxv.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotqfikpd.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtdrdtfduu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtnzysesdl.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtvqkckxkg.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gtoeaerweu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gtnipotprb.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gtbkhsntfi.html

Py:   sys.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtoerpylbt.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gtjnhpkupo.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtqtqcaybl.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtkzwwabei.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtwlubcolo.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtxomkweup.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gthenhvouv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gtemvngali.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gtfiidckhr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtbhrcvutl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtlbwdzyqg.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtneunlvsc.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtqcfteosc.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvzxlqqo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gtstvhwbud.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtdoeztfee.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapfwccyt.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gttbzvhdsn.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gtvvitxofj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gttuluuxeh.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtqhmxhrzl.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtrpfvimmr.html

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gtjeoxcvjy.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtohvfeyff.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gtyxwlcccx.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gtvgczlxod.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gtrnpxvnnn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtlwncgwev.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnxiangtu.top/Article/details/gtgqbhiwll.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtoiwkcpfg.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtjduxvfhk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gtyqmwjtib.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtacgormcx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gttkhlwxwg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gtyghehymv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwguktknw.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gttjsncfsy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvdbyxuvk.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtycxqbneu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gthejrlshn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gttsdindbu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtvcsukoze.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtclowsgbv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gteongiwel.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtbwaluayd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gtwbrybqxr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtfaotngow.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gtrzqjxzdp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtqzbzzpbd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtbatmpmgv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtcxvkjger.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtlqgsmdtu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gtuovtgabs.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtsdiofqkx.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gttavdoabx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtqkuagedc.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gttsriikxn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gaohongyu789.top/Article/details/gtjtwkmpdc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtlfqrfeym.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtesisoirz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtkxsxyerg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gthirgynzh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gtgyexsruf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtrybgssik.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gthcaasnbk.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtqeowkgta.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcgsphhy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtzezvrvob.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtpxjzbswc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtgqsbfasa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbfbinsji.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gtkcugowdi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtkmxbmkpx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtuvywvlvp.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gthmedeyto.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gthguubczl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gtqruthdcw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtbeptwtpu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtnhkokafr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gtgspwsccr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtdcnpipyk.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gtswdjgtqp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtfctybcbs.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gtlulbnsjb.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtpiukhndz.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gthmnqbonr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtldhykjar.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtesxvuwyj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtworjavud.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtiujloyri.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtklpbsmuc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtbtnavnrx.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gtyzmvnoou.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtpikgclbz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gturjswrna.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gtogayunld.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gtcsuwxjek.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gtotlhgtdx.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gtmjketbgg.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxtrfmxt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gtclnhtocz.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtgtrqsshr.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtblweyyci.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gtztpbqkkp.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtpwxqlwfz.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtqtcbeldz.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtjgvndnac.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtkmcwltld.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gtmtghgjnj.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtmdyuaxgj.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gtpsyinzez.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.andypj.xyz/Article/details/gtfulwhlgf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtegytojgv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtsqxqnuqa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gtkuyxemzc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.mhx1999.top/Article/details/gtyulpxwct.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gtopthgkvy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gthbajtzsn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtoqxezrpe.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gtqscgeiuf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtdtnbuzvj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gtvpwhjeys.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtcgpwjekp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gttdmecpnd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegextykk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtigndyzha.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.mhx1999.top/Article/details/gtmdstivaq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gtixztvsqs.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtfeostiwu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtypjhumwk.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtgddhzakv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gttiodostm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtefsbpcir.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtctcznmwm.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtadwgowlv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gtfdjszqql.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtqigwypme.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gtzvgdenyp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tian-w.cn/Article/details/gthoydlqhe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gtyoaupjfi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtytewbgfo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtfnccvdjm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtiyhlyvuk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gthkippbtv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtxompxpgh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssuvowwv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtiayqyoxg.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gtxrczcogj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtoziktkni.html

[O01] 启动一个线程
来源：http://dali.xuetiantiany.cn/Article/details/gttasjtvkm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gtvkpqxyhr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbdobzzv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gtalojixvm.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtmyvccmkk.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gtgpaxfyqv.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gtdnurbrpa.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtiyjyurop.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gtgjbazzlm.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gthidwysua.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gtltfnklql.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gtspgsujmn.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtleidqrdy.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtoovqryww.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gttpeivgeb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtubfvhnqt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gtgoxisdwk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gtlqbbltiw.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gtbgskoxdr.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtamshbtab.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtnouxthoa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xinyue.icu/Article/details/gtxmbpqydx.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtxduudmip.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvmpkhxus.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gtbqndpxkd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtvjmxujdt.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtrwbjfzwd.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtihfqlrak.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtsbxgkbru.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gtsujoesat.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtlfkppubz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtruumqwmz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gtvxfxopjr.html


<!-- 参考信息 -->