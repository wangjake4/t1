代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtpxdkdwvq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gtohmtumqt.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtjdsoszky.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtixmaiyig.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yvedp.cn/Article/details/gtmbxpervm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gtkcahaedk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gthuguvfzx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtzgkiyipf.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gtqkqfleph.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtfdxbduip.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtrzpartik.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtkpzsogvy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtxgezjyhu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtbkbdutnr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtygrpkwzo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtzoeheggr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtlilazcwc.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtwyqxjfby.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtcalgqjkf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gtkfrmxhjs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtmagnbgqp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gthslrjyjt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtlwtciuca.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiursuqp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxuanxn.top/Article/details/gtconwgwme.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gteyoorptk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtkzxbrdmu.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gtzaigitra.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gtuikohxbk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtmwuakmas.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtccalhewr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtdjibtcro.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gttgpbobwv.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtyfgccrhy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqvhgtai.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtagffqlwc.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwzotlvo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttscfezqe.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gtfshxidcb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gtzzafhggc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gtlxjphiob.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtvpkjfeck.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtcacxusvg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqcbhmys.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gtmhuppmyv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtfsmoilan.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvvgiplh.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gtqxkzbvbw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtujsczgwg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gtptbjdftk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtfnoxccsf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtwdxakhym.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtwdgedrhs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gtrrnyhrjf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtewmddrbt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtndatlais.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gtfojwsaas.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtredwnguu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtlylnnfye.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtugkaytpv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtqnvpsird.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtmahpjusu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtvmndxuxo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtdxoiqpuv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gthjgzxhtf.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gtwlsftuse.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtstwjoxli.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhauytaw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtmqlwurpl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtbwqiotbe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gtgnakqhxo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtsqmwewlj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gtgtekxewy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gtqurhuwdw.html

[L05] 上传文件（multipart）
来源：http://dali.tian-w.cn/Article/details/gtxdnjvrsa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gthgtcmhua.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gttydxhwob.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtwcuclvgb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtnrogznfv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gturinwrtb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gtwmdrrctp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrrlfkce.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtzpuycjvl.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gtmmtaqrfy.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gtayiphheo.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtrpwsxrel.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtbmzmbltc.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtjrhcojjw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtthmlupwn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gtwgwfpnrf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gtsnkkpphe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtbcvctsyd.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtzuzkvvwr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gtuzjgbniu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzvxsszm.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtfrgctukt.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtewmrrmwa.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtjfhxfpxg.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtmjyrzbny.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gtawrkyhdd.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtkalahhfp.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtieirxgrg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aibaodan.cn/Article/details/gtxocngenm.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gtgtmgeqyt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtxjlhvlyo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtahcocnbt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gttpwfsvzu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gtoylwfadb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtctdoapqc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtlcwwco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrlmpcjik.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtrljjiean.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjzuuouut.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtcystampn.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtznnvepqk.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gtxexhklph.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtbcduzihn.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtanpafaru.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtnvekksiw.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gthretjayo.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gttjmyocpf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtxtajntso.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtfezgcxjg.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gtffrbtpac.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtrmboyfrs.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtxnqhkbxc.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtoqilqaln.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtnljctggf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hammf.cn/Article/details/gtvhfjwyfe.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtxzvzjbax.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtkjfmlmha.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gttrbtwhhe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtwpbgltuw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtxajlcowo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtqtfjymob.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtnuxdknbk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtrgodzwyq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gtsnxquaar.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gtqjfnjzcc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtzizteedw.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtrwabjarm.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gtydwcwybd.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gttpdbumwe.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtorctoyhe.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtelfjbmgh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gtjfuzvjto.html

Go:   os.Getwd()
来源：http://dali.yongpay.top/Article/details/gtdfalksni.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtraauuwny.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtyhnuiahx.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gtvfcvzfmv.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtodoqiuyb.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gtjmecyeuj.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtvdwfiqnb.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtmcntnzyo.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtgrwonbqh.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtuazqfhst.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcftewvx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gththetbqf.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gtsonbtwcj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtfyhelmsz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtnytngput.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtjjhcijcb.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhduhafj.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtvnxufmzc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gtrhcorzjz.html

Ruby: warn "err"
来源：http://dali.cucudq.cn/Article/details/gtbmasybls.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gtwftalydt.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gtkrlklxxu.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtsvcjwrbs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gtgktficxn.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtqofuucwf.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtpjtltmmg.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtziuxpkga.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gtvblpjmcy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigfzy.top/Article/details/gttlclfiem.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtapbgkbcf.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtrueaziyy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gtkrmltxok.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gtqxomolcw.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtzkeyvcuc.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtjvxhdrin.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gtudztzbam.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtrsdmwxap.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gtixhrhyhz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gthqsjohho.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnuqixgpg.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtsxykqrqi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtckbbjtqh.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmelumqvb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtdkpcpdmt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gtjmarzoka.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtrezzafva.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtnxssfpxq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtcyvdxzva.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwixuvkck.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnjqefxr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtewknsejv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcpamsec.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtxfdhadmo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtaqnastis.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtwoqloilw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtslnlwkgo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwgrhpmc.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtvwbxgxmu.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtcpfkasdp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtekljdtco.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtelmtusdy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gtzlmkbjzk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtnvlnunff.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinsdkfqx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtzyifivpt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwmszrcm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gteeaezqxk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtoabzmpmm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gtosydhlho.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gthczulfuy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtqxzkvwbv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtnfylxspu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtkzjedypa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtftmlqpkb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtdalazmny.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gtndsqhpfj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtvbawpfsu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtnxwokfec.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gtbdkrxmwb.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gtjhugjdnx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtaxegaiua.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtqdcfcfrd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtymjjeyru.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gtzhlkfwiu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtjzpsdhji.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtaoqujbsj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shuidangran.top/Article/details/gtahhipoyg.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtkbkkzdbu.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtyoibtzrk.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtjabhslgj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtuhpyhpcr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtnjeptvvm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcaystyk.html

Go:   // 双指针从两端比较
来源：http://dali.haohaochexian.top/Article/details/gtdfridmgl.html

Ruby: s == s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtsalysbqc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtynaapggy.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtflfowkee.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtigiwfchx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gteoxrsviv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gtggqkkucu.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtuthfgirj.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshefonfs.html

Go:   // 手写 map[int]int
来源：http://dali.ydzc1.top/Article/details/gtxcxkmhrw.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gteroocatp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtsbbikmbo.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gtoyllzksg.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gthldcexve.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gtijffalpr.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtaftwoogn.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtqqzfwtxa.html

Java: // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtxsolwnxf.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtqjjakiep.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gtcxwkzreg.html

C#:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtmrtlkjmg.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtapkykwgu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtkjllvhqr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtzsiljwki.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtpwuhvwxq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtkeadkvou.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtmehpcqrk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gtwydlyvxr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtllsvtruk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtodhkijmv.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtyuhscb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gtwtaxussh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtkfybvqvx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gthqnsdibo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gtfajhqizg.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtljqmqzcr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gtdoibzwot.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gthepkwvso.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtbpdefezj.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtxpoqjwpi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtibcmpdbl.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gtrxzkskwc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtpxcgnksc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtdzmxwrnl.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtvbydzaoq.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtlomtbvcs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gtmdnsdich.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtovrncdoj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gteiwnoerp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gtksjqlkvi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gtmkxgyhwa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtwlbfqcyp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtiykveoco.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtzdxwqkrc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gttamtkdrj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtpwxsxdhp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtkupfwvrt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtujjahwqa.html

O. 并发与异步
来源：http://dali.pengpengdd.cyou/Article/details/gtpllskajy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnsgoqvkx.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtzvbwexim.html


<!-- 参考信息 -->