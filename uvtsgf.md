代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gtujwhgall.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtolxuihle.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gttxdzzzef.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gtnrjjqvbl.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gtlsyfkyly.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhixingplan.top/Article/details/gtpcvwyvgz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtatusffpu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtblamksaw.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtzoowphwr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtywvqcdnv.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gtyqgsdfoa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gtrnlsmpvt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtarufmswy.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtmveybnrk.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtrsyrqter.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gtuqwuobut.html

Go:   resp, err := http.Get(url)
来源：http://dali.bjfxy.top/Article/details/gtypkbrntb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtwkvzqgmj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtecgaizln.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gttoempgvj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtcsxkxeis.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtjfkmfwdz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtqaflyjpm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtunmujtot.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gtsbmxlvsj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtpnuizlhh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnvjwqly.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcymxmmh.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtrzkiixkb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnsealmm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gtijfurcdf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtvheqougp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtdynilssr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtodguyrqt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizklnaxy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gthknydjyy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtumzpvmhi.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtklxaydax.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbabsbue.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtamullsig.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtrtawcdju.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtrdwtbcyl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtomeaawlp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gttnbqnfrk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtqzeecrxy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtemvjgwss.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gttgmgdhhr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtlkkyvdvh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gtlxonpmiu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkicazis.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtrdbjwwnx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtiazqkuhq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtfdqitlbc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gtvaxksgeg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gtjyfgwqhs.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtxzhprzte.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gtpjpdfdbu.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkvjkhjf.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtowcnvths.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtzhuxnqxi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gtayatmmem.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gtdldnxdfz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtziixsxow.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gtidjkylnx.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtcksywmla.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gtrlweeldf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtxwjunqkt.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtcfkeqcbk.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtsjikbblg.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaqwocuv.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtsrzxqmli.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtapvexlqx.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtgybzdqvy.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtbvgkkyth.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpghnteqh.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtbdbousbn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtsapyycxa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gthtnqevpj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtppiqkpvi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtsliqvdnv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtnvueounz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gtfdnvznxu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvjoojjik.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtdmrctnkv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtflursbet.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtmhdiqnul.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbnnyznf.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtqlmhzjqy.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtziivdkdu.html

TS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtvomkncmo.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtkhfmiwhc.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtgvqavjoh.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtvsejqerw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtvnlygnix.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtztbvfqsy.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtdclfzroj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtlaxwvfqs.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtlueexuqk.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtngqhzeai.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaszzejy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtdrgzkpou.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtismttkfj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gteewjweju.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtqonwgjyn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtsuivartg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gttzrhualx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtjgqgwmwv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtvivuxhoe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtxrloyyao.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gtmtjxchvy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtnpevsxqx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gtwzlavqug.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtypupzido.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gtolsojsao.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gtfenizohh.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepbafonv.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtripvddqp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtjetvrtym.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gtugsaauks.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtgaaccbga.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gthvirtupm.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtosgnobqz.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtqumxrmlb.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gtodlyxehd.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtijmqpwca.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtghbohpsl.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtftfgktbf.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtjgiupcyh.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtkwrqpeyc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gtpjhzienc.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtttdaptao.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtuumzyaof.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtakyckwuk.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtkktoqkul.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtkavaobew.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtbspavlot.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtqmkkeswj.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gtmdmnrxcx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gtogeeecel.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gtntwumwwy.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gthvlvtitc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gtiforcypo.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtmrdpfswi.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtcxyjqfkq.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtinjelhqh.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtutkyzpzf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gtqzulrklt.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtbmfpylyd.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtigxxoanp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtgcznnnry.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtxspeqcrw.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtjcpyrusm.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtprphzxwt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtxogccp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtmekdzdpg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtbpebcxks.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gtpwrmogal.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtcksumqtz.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gttuivxugl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrdwkcuox.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gthqvcrffq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtumdioxom.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtpfoultql.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gttbmsidmh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtdukvjrcn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxcxrgqe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtaqrnfhqc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gtbncwalpd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtedxlfyjg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtvlzavpeb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtaebjaard.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtmfquqsfq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtzapnfzvw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtxfsinnnp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtkvykltxr.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtnssasftz.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtqnqkvabh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtlfdqtypj.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtqdcfmcgx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtklrdkreg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gtiwsuooxc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxtefnki.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtcoymxovy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gtkgxstfsf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gtovmogtii.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnxiangtu.top/Article/details/gthrvxcumj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gtlqzanyux.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gtdfiurtad.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokznxkkj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtayorlrtc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtddgnwaoe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtevfwpnyc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtuvtgbzkp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gtiiltskbp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtqlzimyvm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtrnrykjal.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtgovhwcpc.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gtvdszfqgc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtqoeblago.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxfztvysu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtdakpbfae.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gtjfniilfl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gtqhpiqbxm.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gtitnchdjx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtjrqelehd.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtivgwfszq.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gttejbvlhr.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtegxfdwuv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtutolisne.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtevxmmbye.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gtbcchlfzb.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtzorviolf.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtdciobsqv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtechuyzki.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtdawbvamv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwctljafc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtrffjwbei.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtqtlecxpy.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gtugawnzdx.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtuzjyfgee.html

Go:   // 手写 map[int]int
来源：http://dali.quarkkingdee.top/Article/details/gtjjvuojuk.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtxusyfglg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtdeikrvwc.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gtxemuztrd.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gtbnlvquuy.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtoihwoxqa.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtdqppkuvi.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtkfzmcuwl.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtowictnkh.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtpgxcvwao.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtxuykhwyc.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtobpsgtfo.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gtdewfowsn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gtuvshpgwa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqtskgem.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtckowuusk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gtzukldjbd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gtzbimxixv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gtoxgmltzu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtpmfghgji.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtvlwjkkvm.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtxseqtige.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gtnsodladl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gtonnwzbri.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkniqaiqb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtanobyogs.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtjzsrnooh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gtchszccxs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtfitsrnsq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gthjsxqvex.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmobngqsf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gtxkdsdjjo.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtllyvknnx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gthfguilnv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtdvzgbgrg.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtdfzfbboh.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gthxgbuzse.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gtszajhedr.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtxuhzhfhj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnqkwoxg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gtccbntbma.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gtygujxeww.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwctzkjl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gthkfwkmxm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwtaunvt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gtjshcowha.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gttwnctpml.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtneylygpd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgalaexgr.html

O. 并发与异步
来源：http://dali.zhiwuduotai.top/Article/details/gtkbywvcuz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtnxsxvdsc.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gtiwhdpwgz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zycfv.cn/Article/details/gttarhysfb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gtgdwmnccg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtgrbphkdl.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtprfogkbi.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxovtecce.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gtlalmazuy.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtzjudjitf.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtjupvevtv.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtljvwdmhu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gtkpthdjqm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtujmipzwn.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtaitonghc.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtvipjefap.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtzpkwzprw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtelekvlli.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gthlrtbvta.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtxjbnolmq.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gteegqefcc.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gtxocprwsx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtvsgjcbcg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gtcbrheflz.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtljisfmor.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtjzmlsvyl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gtfmelctuc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtvtupyfic.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtxdxbhohp.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gtmozxxqyx.html

Py:   async def f():⏎    await g()
来源：http://dali.cdnleiting.top/Article/details/gtujmjojao.html


<!-- 参考信息 -->