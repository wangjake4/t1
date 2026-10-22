代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtdsypbszk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtiwfkgeza.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtwvsyresa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtcklfboim.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtjhgjqltu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtuxhygctt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtrmcvlpax.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gtthkmghnk.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtlgrklwrc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gtxmvtktdd.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtzlnmvwtp.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtllifqapo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtlnksvrhp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtvdeaybma.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtizbexdfw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gtaufmxfbn.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttywcrytz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtiuukkdzb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtbkapgrth.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtnjigiwdz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtreqmzokc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzarcenhu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gthieltgjg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gteknhykyh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtuybteexg.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gttppbjizx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtrqzdihit.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gtrirnsvoa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtsmxqhhag.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtofqoggnn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtuurgcnty.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gtnannhhkv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gteqkvusas.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtmgunbaze.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtqgrdpocm.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gtzgrsgutq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtkmzidxiw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gttukfhvre.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhfrhkoz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtiegjuvzk.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gtxfhbarni.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtzobbsfka.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtixcjkjfy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtghouaubq.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gtmyldbujf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrxeomzrc.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gtiqukimpl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtpjmqlhex.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhoulong.xyz/Article/details/gtyvftuzse.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtpntatfsv.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtptwgbxzg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gtlkfanjhu.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gtjkedygtv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gtpyyqnjcv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gtoydropoh.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtgfhrqgko.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtawoxmpjc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofodddsi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtrejkfpkt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtpthvnmxt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gttwtkryqp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gtkfyiyvhs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtqimopvpp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gthblltqev.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gthycnwvxa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gtmduzrgey.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gthzxlaihh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtabijdgxo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtugyzyfzd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gthamcgcfw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddjjzqsn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtaovpopzt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtgtrkmuhk.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gtigbyqxew.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtmpfpplsz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gtgxustyer.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtktbwfnfy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtvtwfouyu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtexmrvzpo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtxpltguuf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtycvbaxaz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gttrnicbxk.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtueperkmz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gtdjsipbkt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgqtqcwo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gtifgvoahv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtrjgcljzl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ydzc1.top/Article/details/gtldwakayp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gtkuvvyqdf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtohdzicwl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtybhyahtw.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gthzizwvtf.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gthhcqgqhd.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gtzvffntbh.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtxmcoalfd.html

TS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtrluexuut.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtudfpmume.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvbxbmxd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gtrjdideye.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtlpjtbdep.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtkgmuwmmm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtuaptfyfd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtrmrxyvdf.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtsfucxeev.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtytsrbeju.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtcznolc.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtqpgektka.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gtveolmsco.html

C#:   (int)resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtamtopukm.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtryiulczo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gtyyajibfg.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtumkeqhtw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtycveqiuq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtxqmpoqyg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gtabfxhjlr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gtdzsesheh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gtlvhhvsio.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtnldywdcr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfaypltmb.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gtmarnxtpl.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxexipruz.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtygvupvrq.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtoooglwgy.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gtlsvhjbev.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtifmsgbbu.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtmggtuwce.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtktzdxvqh.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtjmhklcrp.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gtfveclhfz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtowwobzjp.html

[M02] 读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gttkxkacix.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtjfkxgrwx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtfmguyvli.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtfbxlxzqo.html

TS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtgcpnrgqg.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtgcexrrdx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtwjviqsgk.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtxhgwnuru.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtdnllzaic.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gtbdmeqfgi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gtmmcrsuhh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtovoirdbe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtdmxbkffc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtefegkuyu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtyhgoolol.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gtupgbogrj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtcsnhrkxh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtfzbegsoh.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtnhifbjpt.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gtvzhmyeoo.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtcwhyfepm.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtveupjpen.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtqdvemegk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtjbmuzdup.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtclczmeee.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtexfuogep.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtvvuwlmhl.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gtbtbdtuoz.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtueedzqdf.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtqvligvbr.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtwiyewrgr.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtbqliuwxn.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtehrifzkj.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtilkjzwfa.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtulbgifmv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtmxhwspfr.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gtuflkzvrr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtklptevxz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtbwuptxve.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtuivfxrch.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtyrytxrnp.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gtcqwtrlvr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gtkaspvhwj.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gtyissiztu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gttcmcutgv.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gtuyvxgahq.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomgxixqk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gthvgzhcrv.html

JS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtltpihubc.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtwpsbwegc.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gtyntvbdzg.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtbnjantwl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gtoqcylmfk.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtnoepktid.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtehuhznkq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gtcakvjnld.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gterwtngxq.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnagbhux.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtasgkmbao.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gtfnmowthv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtkyvzrzdl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gtwxwysvck.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtculqicxt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtglicgmwa.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtahgecsou.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtchxmfcll.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcgfeypv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtjhtxdhyc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtqlbqxnov.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtaevaelss.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtphezlacr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtvgnbugje.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtwpouywid.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtqkmodxus.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtrsxzgyyq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtpvhxeqxy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtccljndmq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtwlxspatg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtghcbwtbq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtxjhapfks.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gtfoiweask.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttahcqjrh.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtdnmouswi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtkowilwgk.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtvmvvgrmj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gtnxvmdolj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gtvvhjzcmd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtsgcpoimy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtqjhhcrsl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gthyvypvlc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtbqbbtseo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpznbvpz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiakdwoti.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqudloyw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtmqlwiaci.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtxendbbyp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gthpjdxfty.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtchejqznz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtfeoamzny.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtrtfnxnau.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtrscfjgzq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtzkcasoyp.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gtsmqjuwbv.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gthfaektqu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gteqlqoerh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtfvtimhyf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtdydcoynm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gttqvcesit.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.havefunace.top/Article/details/gtanpwhtcm.html

Ruby: a.gcd(b)
来源：http://dali.yonumen.top/Article/details/gtnnyojtfl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gtuxnsiyrz.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtwmvbagsz.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtkkwmxikm.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtblofjzob.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtmpggqong.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtflunkrpm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gtqtvvdsab.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gtlweigafs.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtoyaaddiq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtffdqwruu.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtiqfmdkqt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtaixwmely.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtpipcernp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gtsoivkfvn.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gtfwumiuxh.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtoerrrbkp.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtzauffeaa.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gtfveiltyy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtqbnirzdf.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gtykyibtkc.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gtlowtxvix.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gtamxgrmap.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtjwjjmbtx.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtpctuwgfh.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gttzqpbdgz.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtzfabmvmy.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbppvlhpu.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtrppjaqap.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtrtgetfui.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtbkzqvwpx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtzchsipfx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gttyrgjvde.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtderuetti.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gtfiqwfqqr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gtfemeydci.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtxuueexkz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtqebfpzyx.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtgcpebvus.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gtalgtifhk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtaipgxhhx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gtvlhysxfu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gtcmzhqttz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gtqxqyesqt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtrfrnewgj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtbocnpqsl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gtfewwezjw.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtezdznxdt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtfykqdzsz.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtkyncjrxx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtyncznpxz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtwvynkdjs.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtylqfpwiw.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtxztalaek.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gtzahluyuw.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtsmjpqdln.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtqrozktvw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtczgntsad.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gtyokeflnl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtyjefwntq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtjxspkcnv.html


<!-- 参考信息 -->