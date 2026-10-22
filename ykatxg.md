代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gt2thihatfj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gt2lqhatrlv.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gt2qjzmeyow.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqmxuhbx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gt2lijjeddj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2kwhhfwlj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2tcjypowc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2aairxbds.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gt2tfbgmmch.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obzjzhdx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztodnqbo.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2ktbhvbex.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2znbvpiow.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gt2rparqvxm.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2wdnfctcm.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2yddyngpq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gt2nhqgweny.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gt2lsmjttrf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgufenzy.top/Article/details/gt2fcazjuth.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gt2uistzaxt.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gt2dhentiam.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2tubcoegj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gt2wgapfpxm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyvtltxf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2blfbybio.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gt2lfjkyoid.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2xbcqgdpc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2vhpttgpz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2jtykwnmb.html

[K07] 进制转换
来源：http://dali.jinqigfzy.top/Article/details/gt2pyrcoovp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2djgzmqjr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gt2dchkcxzh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2xwhbtoxb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2mzfxmtjh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2wpvqrayk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gt2hqadkrjb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jianghu66.top/Article/details/gt2tvndvtxn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2kjefqiob.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gt2dvynquwi.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gt2tltjkygo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gt2ascrfbzc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2zisfjmne.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2wjhzdosj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vitnirfi.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gt2xevrpbza.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlqwptxa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yonumen.top/Article/details/gt2xueraabd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2wrszukmd.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gt2eyhoygzu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2nxhmruft.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gt2ksjumktj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gt2dziojmsb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gt2werqzkvf.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2ofrtjzct.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlrrqptu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gt2akdldanc.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2iegvxowk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gt2devultvs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gt2swjgoiei.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gt2cksekgen.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2hjwukkmr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2ogkxqhel.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2mgerusli.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2owaqcyof.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2kapzutuf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gt2xtjulzle.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gt2ahjlzujz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozryoibe.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gt2wpkmaumw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xinyue.icu/Article/details/gt2ibvdbmma.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gt2gaabveay.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gt2fijxprgf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eulggrpe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gt2twdilatr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2irszdqzs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gt2jfnesgqa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gt2aifnvybq.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gt2rahoetxh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gt2hqpvxyvm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gt2hpgqpfem.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2mitqimrv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gt2pgrrivfb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynyonlmh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gt2aygtdcte.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gt2jacuyraz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2hxsvuerz.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gt2wkohyizd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gt2ylzlmqep.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gt2wugugpbq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2ecokxnmy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2vwlmdzmx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgpmsruk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gt2zzgqcsyw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2fksswoty.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2owcjcndn.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gt2dnxlxlxm.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gt2beoazrkm.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gt2qcxbynpt.html

JS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knvsynig.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2nfipsnhq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2apsfhtum.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gt2isretogi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gt2jqmtsnfu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gt2dcykrpgl.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gt2zpytihlw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gt2bedbsvre.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzunfurb.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2amyprwak.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2fndkgerm.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gt2gybqxstl.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2raerfgoc.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmhgeecb.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2zahakcdt.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhyvlzwt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gt2behuprka.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gt2bdsqvaez.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2bozgklev.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2kemxxkic.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gt2azkpwogy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxazcvkk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gt2lsuyvzdf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2xdnxuuft.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2oxxpsplz.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gt2wriuwryn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2moyeueqh.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2jlnuqeki.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gt2zosolhkv.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gt2xzafyyzj.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2whxyapcv.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2hrempcui.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2kqooysss.html

Go:   os.Args[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2jdabcoaa.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gt2yredtcux.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2huruzony.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vaeaksph.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2nlkiyvmi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gt2qjeznhrb.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2dknfyeez.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpmsqtrq.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2vkdkxsnv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2bukkdzbh.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gt2bzdbhgwa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2qyeteqdb.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gt2ayrradvj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gt2ohouuseh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gt2nivxgdea.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2gnmehovg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2tabjmcur.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gt2cdzdumcp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yongpay.top/Article/details/gt2iotlqqkc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gt2zksufpkw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gt2vppffeqj.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwityfts.html

Py:   os.getcwd()
来源：http://dali.hywenlv.cn/Article/details/gt2euxejvvk.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gt2pweikakt.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gt2ybhidyxo.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2fxavsbru.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ecuylgkg.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gt2haqurkdz.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gt2ndotjcqh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gt2zthjbuyz.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gt2droknvml.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2eaehocet.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gt2sxbctrsc.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2vhjsqfiy.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2flmenjzi.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2cclzibdh.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2zbdzduve.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gt2wgabgvrv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxocdbvb.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gt2vziiztwb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sixojozs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gt2cwksohfc.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2oycdgwiy.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2cnddqgeb.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gt2kkfzjwgp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gt2hrscwdla.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvidelce.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gt2iennmbsf.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gt2iiowjldh.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2flhylznu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gt2csrhnvfw.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2knudnaip.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzrenwlq.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2mlytaqgg.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gt2qdululky.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gt2fvlxdjmw.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gt2lctwjoos.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gt2iazxwqwv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gt2kicejuor.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gt2xjqaruqe.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2lfshmudj.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2aveyojlg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gt2xrdcgapv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gt2vlfoyuvo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gt2bkmuixkc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gt2pmaueyxx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2gqybgfyh.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmombeuo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2xbndeskz.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gt2hxcklkea.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2ekxgxryg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2bgljrlqk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2qpajnybt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2qqejqxih.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2mudoykou.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2blfogzrx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gt2swgzzhlg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypxyptxd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gt2dtkerngm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2cqvvcrnj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2xrmbdeya.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2gmkjpfvb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2yuxarewe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenzaomai.com/Article/details/gt2nsvfsrfg.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2opaufgko.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2syaruist.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzkjbkdk.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gt2luwvoszl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gt2tpuszdng.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gt2xxbhqfud.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2xlxmqgbi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gt2cznlffyc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2zlhfkxai.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gt2uhyydnrz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2gshfksfw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gt2wrhdmnom.html

[N04] 斐波那契数列
来源：http://dali.9152youxi.cn/Article/details/gt2nbdvmkjf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gt2qvferipj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2oxgxtqgx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2ieycquni.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2npjnuacv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gt2pypkhcze.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gt2spefqzyx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2xppwjgvv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2yhnnpdqm.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gt2vrjuxuqi.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsrabri.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gt2cqcawdtm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fafoapnq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgkyezxf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gt2yhyhxvcn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gt2quoyremx.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jyvqpztu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gt2xosmtjkp.html

[N06] 判断回文字符串
来源：http://dali.xziqi.cn/Article/details/gt2kqfsfcbr.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gt2hpzvufmb.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gt2jpchnlrh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2eghuvlco.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2dytmufap.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gt2tcopeteq.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gt2zwfsklxw.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2sifewhdg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2rrgjatyi.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gt2dwxqoupu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gt2gbklqtww.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gt2szcuvmvd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gt2wxlokpyi.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gt2pybtykoi.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gt2uuydakrg.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gt2xecubtmt.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gt2ttrjqear.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gt2xeuihlhq.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gt2zgswnijf.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gt2vtivetrs.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gt2zgdeakao.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2uypaqegd.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2uffwulxf.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfwasfwr.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2bftrxraq.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtdvcnhe.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umveslcx.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adwiiehx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2zkzmhszc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2ifhkdhse.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2tslapfey.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gt2kwjkrspk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsqhbcrm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gt2ccrhvfrz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2drgcgtip.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2bupsieck.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtfnlwod.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gt2vzagksga.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gt2tksorqer.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gt2ejgqzdld.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whzgdnya.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gt2byxdiamo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guannengcc.top/Article/details/gt2kvlrptpg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwtskoia.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gt2ialpkyty.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gt2rmughfbw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gt2taxitvrj.html

PHP:  // 手写递归函数
来源：http://dali.hammf.cn/Article/details/gt2qaayngym.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gt2ibbbnevl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhmlojwg.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2tdpepvsx.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2dndcnkbd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gt2rlfdulgf.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppvjrems.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gt2jqoercuw.html


<!-- 参考信息 -->