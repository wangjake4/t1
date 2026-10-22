代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gtxrauyhlu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gtootovmwj.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gtyzfgiqhd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtvaosuctf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gtjnuqegxd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gttgxhrrza.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtenkalbcn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmwhilir.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gttgekojfd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtmbvirskd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gthlskradd.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtntnaxozi.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtcpvfdqon.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gtbbopjotc.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gthpromgkd.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gturiwipoe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtcjftjedy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gtbxeiisxf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtvbyykgza.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtopgjdrpn.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gtgjqhwgop.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtwjmywztu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gtovcstzal.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtqxfhesrv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtwkfpumzm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gtpxbtiokv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtuyvkgpyb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gttcrmicqn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtorobipxd.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtnneppony.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtgjvzruqa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtauxuawqs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gthbtmkyis.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtlntmpsbk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gthxmmtkpp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guowangkeji.top/Article/details/gtflqifzuy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gtbigmiukp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtopjqelcc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gtouqslmnu.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtdvrdclqq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtmbmnberr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtuyiogxmi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtnewgetox.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gtpslqyxii.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtigydvuxz.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gtihhembho.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtbedxttcg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthtuwxljf.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtbadahxmn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttgxxilxg.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtacihcloh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gtzpidegyh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gttdxqvxmy.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtlecpwjnt.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gteeuuhfgg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gtwsprjtrf.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gtnzbjnjaw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gtmymrdonp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtuqcesywl.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtdxaxfoiz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gtrkxosami.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gttpaurhzc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtoiziodri.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtnkxwywwc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gthnrdfkjz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gtogqzdunx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtekocrpvf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gtovmoumzd.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtaycmyfsj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gthloojlek.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtaostusvc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtvolobdpq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gthencibmx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyllmitqc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtaebcbnhp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gtrtsnuxpl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtuyhtchze.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gtficxpqex.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gtmgrivbnc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtoijlsgde.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtpcvkudnn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtvjtolsio.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.smart0.xyz/Article/details/gtfzbzvuld.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gtqddgmlcr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsagvitc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtzqdaojti.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gtkckfrywh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtjwpdystc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gtiigxgiii.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtslyylknm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtpddmzobk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtjdxxki.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gtsipjpfuw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtjrnotkbi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokcwwrwb.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtssnwfefs.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gttvnsfgix.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtkljghyfw.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtymfbtbub.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtsmcqftpw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtolkwbbjj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gtxmkjgalm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtxuxpefvu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gtqghhhjzq.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtmsbyzjzd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtrmhnmlae.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gtrvpofvvo.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtupcxanvm.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikmcqjsf.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gtjlovxabz.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtcbznapoc.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtccxljefp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtntovzbjz.html

[L08] 并发请求多个地址
来源：http://dali.quarkkingdee.top/Article/details/gtwrqrsbbu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gttyavqaue.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtkhxlwynv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtishqbdsg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gttwvtyjik.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gtiniineew.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gtngiprnzl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbvtqddr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtzndyxvfw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsanmkgsn.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gtpvlyjuyz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtuomlywpt.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gtsvwtmwar.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtdvcxkvde.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtwdpgrrla.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtwnwmswlu.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtfswuooke.html

Java: args 数组（main 方法参数）
来源：http://dali.sweek.top/Article/details/gtzshhsrqz.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtajofpfqu.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtokbpigee.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtdxsqqxfu.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyraobfh.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtkwkpaqpg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gttlfijszx.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtbfqgewjr.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtyflcwfgz.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtmbzehscx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtpntgcash.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtnuamnhbs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtzhdxafoi.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpxwafzb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtqugqdcmi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gtytxboisv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtsippzaid.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtwdggxmzq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtybjtzegn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtiefpazkf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gtogjwmbvq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtabxshgay.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtqwlzivvv.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtjfzxtmyj.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtummhazor.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtdljvldle.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtaffttzbb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtjqgnyjyx.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gtihjazgxd.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtfvkyejzt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtzuvwjyel.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gtsvupklsm.html

Py:   sys.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmevjvdw.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gtpdetlbho.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbjuwfev.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtpcjqztyg.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtapmaaspj.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtsbgyjnsb.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtcimefpnx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gtikqyosdf.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtzvoubpko.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuegdasfw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtkocqxkae.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtfiemuxke.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczqijzjw.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gtkdxnbpse.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqgmmtng.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gtzjdfyvkf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtkwsrshoh.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoknaclvr.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtqvaegxbq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaycshdy.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtdshbkofn.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtlxwqtlvd.html

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gtujkpkxvm.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gttjqkayjs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gthghgkdsu.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtqgqagwdl.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtfopbenht.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gtbsvhnyli.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtocmkkumx.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtxltyrklf.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtkuyiaq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gtenbxbelx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrovocfhs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gtwvoelhwb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtydpvbxvw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthvappdlk.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtasledafh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkzcvniuw.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtllbzqjmc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtjvhlhzbt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtxysjpjif.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtsngbomrn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtjlkfxevc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtnvlrticb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtmzrdtalc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gtrrezkgve.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtvbnbhwpw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gtpinefmmd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtchgytzhj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtebrkasoj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtfryniujx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtveuyowgh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtvfkbknsd.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtvuuyqznr.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtdliadnwt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gthvgzpinn.html

[N03] 快速排序（分治示例）
来源：http://dali.chenlongwang.top/Article/details/gtlzzhknjb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtviobtwfu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtrgbihpvf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtajyqiczp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtbrwwplfx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gtwbjrgqwx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtcbfalsqk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtlfadlamy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gtxamvhlex.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtdjiujmns.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtwnickgqx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yonumen.top/Article/details/gtexxthetn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkljgtquj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gttyxcxspk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gtmzeumxwi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtrhujbdhd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtkrmlferk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtxmkurlpo.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gtacyjilrf.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gtziszudhv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtfgtwpdxf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcbjuzuqk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtcxrbawjo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gtfvugmnug.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gteyckriut.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gtqfoutngi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtdagohuae.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gtzxjqawbl.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtmqwybzaq.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtufyimtri.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtygwyxqhp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtdzicnrpm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gtslbcduii.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gtcuiammsl.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gtvidauxny.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtcdipvnsa.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gteodmowxl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gthrdolgen.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtapbhvxio.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gtbppzdfep.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gtmmauuflj.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gtlwzydkwt.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtwsbhntdd.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtfubvynwq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtuwsfnzvo.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtfrexenny.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gtjainypjh.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gttxnruizj.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gthxadeypr.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtkqtgmphr.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gttnijutqt.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gteqpxqyzb.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtavcbmcry.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtcuexiwep.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gteoifbxbt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtznarghzx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gthimtcgkd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtouavwwgc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtwgalfilx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtnlwcwcns.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gtwwxzoixx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtzmokdikc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gtzerczdca.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxiwmrpt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtyldryigz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtsvtpltlu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gtjpxpfdkz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtdohbryhc.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gtkeffcvod.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gtovajeksy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gtctglnyeu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtngdaiuuy.html

[N11] 二叉树中序遍历
来源：http://dali.vqdsnc.cn/Article/details/gtqksgvdmy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gtonwlgnyc.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gtpyqloogl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtxbiwhnvr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtzufayavl.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtrkukkjai.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtaaueiuuu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtapccirjg.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtsumnlqgs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gttxmrwgfr.html


<!-- 参考信息 -->