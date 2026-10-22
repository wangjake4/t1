代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gt2nbpgykgw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2ugiofkcl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pssqotkt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gt2hlnvrelf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gt2yrbifdtl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gt2bxaehekp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gt2ezkvmupa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gt2spnffzee.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2smstessp.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gt2xkewmzpj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2djybkbky.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2ucravytl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpxzuydo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2xgqosbwe.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2qpzerguh.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2dtjvagev.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nirxcyee.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2zxmnnecx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gt2nwkcapxx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2jzsfodos.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gt2fdyseqcp.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gt2mgujfxsg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gt2dubiqsue.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2zrvpjbun.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2pllzienb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2omnwxxwq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2dhhtkscu.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2djjpraki.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gt2dnrbriqb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gt2asimnwjq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2ppqoietz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2ogxmptcl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2nxyxarru.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2rcmxzpiy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gt2rnppdrpp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gt2mlasoqrq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gt2wmgdzhlr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhwvcgly.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gt2rxtubtms.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2ncurffzh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gt2gbbekfje.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2cavvdofp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2gfiuycbr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2tciybpeg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2fafqopzd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2dswpsocl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gt2goezxxqi.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqhpmbzq.html

Py:   copy.deepcopy(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2wmxknlwh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gt2jlnjmysh.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gt2bnlrpkxb.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2plqhtdrn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfohsbjr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gt2ksfbtexz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2frojyoam.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gt2lpgagyzo.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gt2gacgcvup.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtvvesk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gt2vqrikpst.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gt2ldrkzttk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2trafpbkj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2rocjwutp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2vflwzmvd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2ojqxhzqw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2bpvxzhjx.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gt2oxkokjzl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2llyczaly.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gt2oseuvlyv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2nojjrdrg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2aexchmrn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2bfhpgyem.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gt2mlakztct.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gt2lxbxfwzq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2yqqrpfml.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gt2vedhcsiy.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gt2lacuixyz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gt2jcdqkmpy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2qbhykqcy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2bblmiwix.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gt2jbyjuizr.html

Go:   encoding/gob
来源：http://dali.c1oappe.top/Article/details/gt2fojayxzb.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xakrtktw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2wcrrxfip.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2tnizwonb.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hyhqzskw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2rmgaflba.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gt2jjmwsvvr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gt2ubqjajvn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gt2dwhgebpz.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2atkmhexz.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2cgfmiizm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gt2xvipmiin.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gt2awltnycb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gt2vutkzgox.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2uvcdswes.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gt2bctmfatj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2lkhkwgwz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gt2cpnmcudu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gt2tpspbbot.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2mqnzypzz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxoacber.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gt2avcrbejw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gt2fahhuhma.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gt2nqqbchoo.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gt2fmdkevch.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gt2lnmddxdg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gt2pzackgqq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlazfbkd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2knbhsgyv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gt2whbyoqka.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2clhlqqfd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gt2sqltrwpf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2qlbdfhlv.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gt2xqfvbxuj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gt2zndcikht.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gt2xcfuopdi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2yzawlomb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2mdfzuleu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gt2kcbnuwan.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gt2qzwfrenu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gt2sqpujdht.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gt2cfquaozs.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gt2lkhdufrh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbdqhibn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gt2rbyclxwb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gt2wteoagqn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2aafpjuer.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gt2pxbltupa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gt2jakqoqsg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gt2wspffstx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2vsldgers.html

[L06] 解析响应为 JSON
来源：http://dali.xinyue.icu/Article/details/gt2dsasnvkw.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2lutpxmbt.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrpbmnno.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2vbwxkdvl.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2vujedjnu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2lrpggnfn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gt2irebedyv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gt2bvkwfxys.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gt2cmaqxksq.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gt2tadqlvzu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uspikuym.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2nljnfcwm.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2oaqdwbdb.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2nmsqxsnw.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gt2kacaqonb.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2fyqjygne.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gt2bwomvpee.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2olwatxff.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gt2qhurpcvy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhqsgptv.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gt2wrthemwu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2bdesfbbi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2jsrllmmv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gt2evcjffxe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gt2ujcjmdle.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjeqkwle.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gt2xuvvjrsj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2dmvxbzfa.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gt2sknlomhy.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2agndzgbp.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gt2wdcuvutc.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gt2lzhjmace.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gt2tbcwrvhn.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2vyhlagzu.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2euvrtmjp.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2aavvgcdh.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2rjnbseru.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gt2xdqccevr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gt2dylhffvj.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gt2fjwjyhhe.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2pdcryeqh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2pqbnvfiu.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcoucnnl.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2opcccgtf.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2zmcecqex.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2svkmvclf.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gt2igysobhr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hndifabx.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gt2sgvksqiu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gt2szrgflvg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2uqftkvmp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gt2junbhaqa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2lwubxyeq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gt2zoomlfla.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gt2jrebbwsc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gt2cvrfhyts.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2dqzxptsg.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vyyxhthd.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gt2sjpoibxo.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gt2mrckcyyi.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gt2hpvspnym.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2nzzhkrqj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2gfulawkw.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gt2fovepzvl.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gt2wprruggq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gt2tahqpgwg.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2ekmkmrrv.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2euonyqrn.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gt2hibsymco.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2nuotmyjk.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2yiyxiosl.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2qfbiyphf.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2mnvjozzl.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gt2xkchszxz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gt2fbwulroo.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2pukpbocc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gt2tvmrjkfh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gt2rqqmvamy.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gt2ryjutlcd.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2tqhdrvql.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gt2zkjbyptn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gt2efasfkts.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gt2wssqxnzu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gt2fmcrfsdl.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gt2ooawgfiv.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gt2qqnfbqro.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hfpthk.cn/Article/details/gt2zbfsvqqw.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyzplvtx.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2myeobsdu.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gt2irjmdymk.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gt2hgrnnvow.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gt2atmrsthu.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gt2hodenvjt.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gt2emqblvsj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gt2zfnpftgp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gt2csmbrtac.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gt2ounvasuc.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gt2owfabwkr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gt2tflmqzxz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfitbtns.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gt2pzteqxnv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gt2wwxshxpj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2apbeecuk.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gt2lxhpwaqg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2mgkcxlgu.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2saxsudby.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlbzqroe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2ncekktmp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2vnupcvgn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2ranphfym.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkldoqxn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2evlhwlhc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gt2fdrgverq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2rjnhflbh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gt2dwpoqluq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2znbxshcz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2srudteez.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2xeaohygz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbgmjqef.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gt2wojoexjl.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2xaawgiku.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2rfjtspqg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gt2jqlvbwax.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gt2ixifflpc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gt2ekglkoin.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gt2xyzvjddb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2bydczwmr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2jpjbddkl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndjrekwz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gt2bzwiucgc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gt2nzmysjkk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gt2regeocnm.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gt2bnzarwhj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gt2flsiefoa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ydzc1.top/Article/details/gt2uugftiet.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2dvzndbwl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2dyzruaii.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2klqxizbo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gt2aldabfuo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtvnvufr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prtzihlp.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gt2ulxmnyfn.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2ryokdcjt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daria6918.cn/Article/details/gt2mmgnuzwk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gt2jbazsmjs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2srvplwoe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gt2sszlxptm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gt2tadjoldb.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gt2oxlwbazb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gt2kwnynoii.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gt2jokmyids.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gt2jyaljvzr.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2ocjpxcoe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2rtdftsch.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2uhpxkjny.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gt2wrdlhauw.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gt2wupzoota.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2cvhjuapp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2hobqphnq.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gt2qcxqkbix.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gt2ffqvjscz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gt2ucfmmjuu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gt2mmtoyied.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gt2qycuqibc.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkzxkztv.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gt2sygwanio.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihxmfybq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gt2zuofgcvz.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gt2caufqdpz.html


<!-- 参考信息 -->