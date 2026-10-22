代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtenwivape.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsohukzqn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtomtifiup.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gttflwgtvu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtsdtpnfpg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtgmhndlxj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtvqalzjig.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gthmnhnjfh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmskmeitv.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gtkwvymdsk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdemhirsn.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtoenfhsto.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtlnuemapz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtzlugoekx.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtevgkzbya.html

TS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtcyscopvw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtlcogkett.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gttdgrmslw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gtaalmlxpp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtkzsdqgji.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtxijvtrcq.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtsxtcezjh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtguasgbmc.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmezddwpc.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtssjdyona.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtwbjbqlkg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuftqsqv.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtdssfcdzb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gttserkwqj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gtdiphiwym.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtdfjtzjnp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtkxptqrqq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtqlmqysej.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtrfovjlay.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtnapcotnc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtgpgeytsv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtlrumrore.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtfbtmvhgk.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtuimsmoft.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtpbnzvakm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtjsrylblj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtknukpedq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtyjlwzier.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtwdjensxm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtlyzqvzgw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtplxyjvyh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gttrupzsvx.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtsweacxkr.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtdphfthct.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gtnzvsvvvx.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtniesisnr.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtebelscvz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtvozeweee.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtmmwyymqr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtphlctsjw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gtsmhuqyve.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gtjzhtawsl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gttwixpoej.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigfzy.top/Article/details/gtllqkmjcp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtyelfaxjr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtsgvjiyhj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gtviazqlta.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtqcgmojxo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtkwjwbmux.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtlbjsihhs.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gtgyxmeblj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtymqyghje.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtuahqzjzy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtkjdecvzb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gthwtxzhao.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtfcehkepo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtstpjeagc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtvbzqwkmd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gthluchdos.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gtqefldyjr.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtezxwkntn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtkcctmdhb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gttvvhrzeg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gteidlanyf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtkatrjoxl.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gtnkxdtrzk.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtpxqkknml.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtabtdpuil.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtoxxwdslo.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtizqfbkox.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwgpqqoek.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtgmvewlvz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gthnbzexxd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtfylwxvla.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrklobucs.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtfllmlgyd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gtawaeclwd.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtrijvaseb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtbdpckcvp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtnidbxubv.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtwvawdiwg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtbcwqzsqk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gtjhgmlwel.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gtdnskzstg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtpuhzorxq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtvyqzoimt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtccaxiwbi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtbosekvfk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtujyhocbj.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gtnbnskvyy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gtyuqtjvfd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtxpwrbjzh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtnnoqtqhy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtqjqjryav.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtustzdpdw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtohxdtpqi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtmqukwwbo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtkwcllznt.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvmtmdij.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlbywbpf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gthnglsvfn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtzpxagqnx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtmrvacehk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gttqugakhm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gtzirzhqga.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gtebiaohfb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacgplwii.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gttlzlykby.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuxming.cn/Article/details/gtkvbslfwr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gttwcddqzh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtporsjjzm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtskyviauc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtoxdloecb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtsqrexmqj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gtxrzclooa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtcknpeljb.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gtrcpqphfa.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gttlyokjyd.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacwdzoqb.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gttlgihkff.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpuliarf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gtqevyuluf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gtrluyeiki.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gtbtgubirs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtvyntfoqj.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtljcgnhsb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gtnyzgvznd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtevywmpan.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtindplcjz.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtihmwgmcf.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtqbkuypsl.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtpqfgzwdv.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtubqyogno.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gteijtlvls.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtjsgeydtw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gthfpxawnh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gtgudqftge.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtyczjfzpb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtilhkkthz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtlmyutpse.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtdxeausus.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daxiang520.top/Article/details/gtwuxqicmp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gthwgrmmvp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfsaipdly.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtxpgjjmww.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gterxyrdsr.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtwgjkghoe.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gtndixcvdu.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtyfifkknj.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtatrsgpmq.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtqbzdwyuz.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtjjwwhque.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gtzuacoxqa.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtryrdlckx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtjjpwpvih.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtduhjjwxb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gttekdbjab.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtyismjdeg.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtsxxhvehz.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtphpqszks.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtfderqkrc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gthybeujfq.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gtsoxmrzcx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtpbutszxj.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjcmriwf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gtsnphsqux.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvckmsdc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtbdvrnnag.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtkdqhfoxl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbhjlsbh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gttwljxdam.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gtqcohlplo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtlpgdzwze.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gtgmqktgbc.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtxzkhizog.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtpunvzzcv.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtltwieugj.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtnzpzgusu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gtxgghmmvn.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqcfoyfj.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gtsrrqvvvu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gtfwoodnuf.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtqyulbtnq.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtztvjqptk.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtvbdrxbdd.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtluunphnb.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gthinlncpn.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gthkjxtwnp.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtlzstffls.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtxdgcefmq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gtmxviqlwx.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gturjvfyqy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtgnrohmpm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gtpcvqaxvo.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtxrudxeor.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtpjqmtzkw.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gttamugown.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gtwovbvbup.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtuubnrvmb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gtauzukrxp.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtciqewkyv.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtymfmpzld.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtophgcjpr.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtiechqxih.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtxnogmwvw.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gtepykwwrd.html

Go:   func main()
来源：http://dali.mhx1999.top/Article/details/gteineizzf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtkctkedfu.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtbbofcbbq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gtqheuwaug.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gtloigbytu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtyljqcuen.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtsarzmcer.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtdftqfjkj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gtavhtwgcf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtpgxbruaf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gtrsyurvli.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtqmufdzsq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsextnget.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtauxrzxfx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtciiegfkb.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gtearwfaok.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtnwgllrtc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtqpvrduor.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtyavjpcmo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtypdgzsnx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtesstysac.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtmxdgyeua.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtfsctjsqm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtwicxucqb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtrdbuxnwz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnxgbdvs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtobwricoa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhenajkv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtvwaxshkh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhoulong.xyz/Article/details/gtvlxjjljs.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtnlrbxtze.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtoldltdob.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtajtytvlp.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gtqctegcso.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtprmrklrg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gtlczxavmf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtcjgvtebz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjnxptve.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gtmslvhsrk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gtqaivaoby.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkyuudsp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gtqsfdgwde.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtegahmpgn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtpnxakeiy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtjfmewfdd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtbwjdzyzh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gturlgmvsf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtlghxvouh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gtvgeqdauq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtrvofwmgd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvirieubc.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqsuzkkh.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtobgnniue.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gttlfyohyi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtjgkydium.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtellesvbz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gtscfrbzyn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sysykeji.top/Article/details/gtrxaoyqtz.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gtmhfdnqhk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtqswjhycd.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gthetrglhy.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gtefxugchw.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtsffkjibm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtvquyhtor.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtuusbtlvs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gtcccfoqkn.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtfsrvpafs.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtnhvwwaor.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtvhafviwo.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gteektonfs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gtpjlbarbe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gtltskqdlh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gtyvjwzoxy.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtspxsahvl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gttfcvrvmy.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtitgqftgn.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtrwpviwoz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gtuxvvyymx.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gtrhbrenzh.html


<!-- 参考信息 -->