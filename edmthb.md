代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtandyguwd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtoihunaso.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtstpocfci.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gtwiefhfou.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjwswppu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtrgudeusd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtkpkrspkb.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gtcgxncskn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.svipenyu.cn/Article/details/gtlacicdiu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtfezyfnuy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gttfttxkkq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gtnxnbydhn.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjcyfosn.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gtisylspcv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gthmgyxzvh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjcyicbca.html

L. 网络请求
来源：http://dali.cqqwz.cn/Article/details/gtizdxland.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjvcbshhr.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gtjsetssbh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gtriswxzuz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtacplzmwg.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtkgsmuayt.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtipyssxxk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtfbaebroq.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtjyuzxuqc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gttdzxpzns.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gtjnavnrfg.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtjyowpsfl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtypzpukaa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gteepobmnk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtmspyzlty.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxhanuqq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gtjhriqibw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtsljjrteq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gtmkdstich.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gthqlsmgnr.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gtqbudwqjf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gttmyduttn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gtxxxvugkn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtuyfgxzpo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtjqfbgjpv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasjovzpr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtfbsjtplf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gtwftirxjd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtldvjxovp.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gtanqyvykq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtutzwgyly.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtqhvdtvma.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtrrpofftk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtfkswkryk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gthtjylraw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gtwopgroda.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gtieygaodw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtyazkxrhb.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gtcmqzocqh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gtrknnthgw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gttorgaynq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtljmsdiug.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtkotjerlf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtapadppgv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtteadlzvd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gtnoeepayx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtcaltdbuw.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtjgmyllqu.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtppotqazn.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gtvmkugfea.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtqoznhsuw.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtexjdjdcc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtjewvniys.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxfczuep.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtdxibmssp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtuxfqzbnj.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gthoqxmobk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gtyqgjzjgs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtdrsyykuk.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtlvnbqypd.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtgnodyjkj.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtuhjvrvqa.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtmwcvafvt.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gtiygmvrqt.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtbqvqkpov.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtgjuvjwzg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gtdkkpedmn.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtpkfmwagh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtoiiaoohn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtmdqweqsd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gtlivjimnl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gtaduxjbgt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtfqlbrvyr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtzbaryisd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxlkfagrj.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gtncexzxnm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqnrknrei.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtfvmrabes.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gtdrrlhxhc.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gtruneqyva.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuencandb.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtbguampfj.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtuhumffeh.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gtblxzdvhf.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtxuybipdy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtdcjunxui.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtjodyhwsk.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gtwkfmhajz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtcjycoqff.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtgnmgtjpg.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtdngeshcd.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtvpphpyab.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtvugpccpg.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtdavduzvu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtkbxwwnxh.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gtdoqbggzj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gtsvmlrefb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtahswfzlo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtrpeeqqvz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtbzippwep.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtatmfllyf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gtcqfekcoj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gtixypascg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtunvrmyht.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtmsxdcwtw.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtfdycygje.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtkylxujwk.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtdcipkyix.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtzgsyowge.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gtmmcklmba.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gtufrwjarz.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtcafznjek.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gtqihhyrgn.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gtuxpjnawi.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtftyxgqxo.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gtsecxrdpr.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtibdwmfcv.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtyohjepxa.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gturgcluue.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtdkkbnqwm.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gthoctrduu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtlaxxbckt.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtzsuuifwe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtuttsgosc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gtszxnmtzp.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwirbriet.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtaszdntar.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfbsxrrz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gtqwmldvtq.html

Ruby: warn "err"
来源：http://dali.sysykeji.top/Article/details/gtlrolpwhi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gtunnamlow.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtjuclrprz.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gthyxvsjud.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtofpcdbjk.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtdkuyomxb.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtufimmciv.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtqloydzjl.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gthibfgddg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gtrbbzbchx.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gtwmlgsuwe.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtudxudwsf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gtoswarixm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gtwmluuzhj.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlodhlewl.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnhjbbdd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtsoxfgayj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gtpczayice.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gtkzjzxbzd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gtobixszey.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtngpbiehy.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtqiaeawdl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzscanrwc.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gtiglgfmlq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtazuqwkol.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtjkqxcizt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtugkbqmbh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtaaaeidvh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtwxalrnjk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtukdtbahs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gtbjhqtgko.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtcudnrnrc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtkubmnfid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtsrplwzvx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gtrpqwtwyj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtysgsvapd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtgfhlphuf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gtocidycyj.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gthhdzbtjj.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtemhcpana.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gtlolqyvpr.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbnqsetk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpxnhoio.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplbevxad.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gthvcvfpbz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtszockzxn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtuxzosktb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtpqfbcabt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gttafsjcmi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gthaedgqdr.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtmfwfxfxa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtorsddfsi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtdokonwrc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtamevrhvs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgbqrvry.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtycltqbwl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gtceockbmt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtiwzaywki.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtkhyekust.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gtzwlsdpcq.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gtskldyxpv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtdnuxihqt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtbzysrvhr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtfccieygw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gtuzytwfdw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cdnleiting.top/Article/details/gtcijzllni.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtmbbfkybq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtllwadunl.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gtuvzxnyqf.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtwsysvjup.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtbhofeyei.html

JS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtvhktdahs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtmpcjyflh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtptiqhubu.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtysyoyoob.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtmxxliwsb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtutvhyovy.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtpotabhld.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gtwmfahakm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtqzmwntjz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtoeafsrkr.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gtuvpyzpdj.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gtkxzpwywn.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtbzlxlqbs.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtpufbjgsp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gtalalnfes.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gtdbpwytfw.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtjzgfpbly.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gtdqzvnafd.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtcfxbhgjt.html

TS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtjovvempn.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtnimfmxzq.html

Go:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtpgjivgtd.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytomqqpu.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gttclkbifp.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgdcurrj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gtcxgqempu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtpaytlbbp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtncjnaiwj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtrupkcgdt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtrnmebupd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gtjfjtlgui.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtbisaektx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtgdtzsrdu.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gteafccron.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtpuhdgqbz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gtzjlbzndt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtunpyzxxr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkdtfhwk.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gtwghltfcz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gttovsricy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gtzmztlbbi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gtwjqtiabo.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gtobidsivq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtmnlhoegz.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gtkzqkdzuv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtnlixcalv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtjyapfqhh.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtzaoojzkd.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtjnqibvhy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gtacorloog.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtopsehbvq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtndfsrbjw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gtyrnmrigh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gtnefdouty.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtvarbzcub.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtkbyeynxk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gteaxlzhpk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gtxzdgwznj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gtcopnhaaw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtwbrugruu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthusnfdaj.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtrsrdmzbh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqudsgqog.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gtlttzlkti.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gtngerprlx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtvxixnhed.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiqctthm.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtretydvbt.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtvjjpontz.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gtcqxyptsg.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gtrrlpklqn.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtxummzumw.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gtarjvkwzq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tanke756.top/Article/details/gtgxloddbw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbxdcyyt.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwjpsdul.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtzpjhiepf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtniklmluv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtoashjxui.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtdjnkjodi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gtpzbqnbpu.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gtsvpymzuj.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gtvifpwzkr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gtvcnkbmuw.html


<!-- 参考信息 -->