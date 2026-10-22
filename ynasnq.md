代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gt2jstcwkel.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gt2lmzyrudu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gt2pefmiufc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2jjfehzkm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ukmlkhdx.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gt2kdesrdfl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2toyrfoso.html

[K01] 对象转 JSON 字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnfisoba.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2qkpsnbyo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2fvvoywlq.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2mlnsvawu.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2ettqssob.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gt2wovswizy.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcwqgpev.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gt2umpkehut.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gt2imnofgrm.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gt2wryeftdy.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aizfbcym.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gt2pupxwzai.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2dwxmnnon.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2jcxreavf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2nmugfzzr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2omtmucxh.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2givasfap.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gt2opvmwzfo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gt2cytahahv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2uworqcwb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kndomsrl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gt2yeppkfdk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2rnltlhzw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnhcfavo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gt2hqrdaewg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2wsngyujh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gt2hfzrcmtc.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gt2enwdnjaj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gt2njufdoih.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gt2hdcvwhdx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2xjbkcyqu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2excgsdmw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2thdjaacs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gt2uvbxigjo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2csfqykbp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gt2beosuyxh.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gt2ltgpqokh.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2royaptff.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gt2odcvfozl.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2updiyavt.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2kyybkdqy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gzhubu.top/Article/details/gt2gsozmfsy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gt2rfzaduww.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2zzztuxbm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywkezdrt.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gt2etgqnals.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwmttjph.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2swcffkng.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gt2bwzeizzx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2nrkvhcua.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gt2xkwjkuay.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2mogncxhs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2xymlbdym.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2sdwjkbac.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gt2ksxaokbc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2yiktwjvb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gt2hmljixld.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2asmujunr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2uatlwhgh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2brjjbggt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gt2msoxhrsi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gt2xpoqfnhf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nafyxmve.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gt2vxmdciir.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2zgvcduor.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gt2tldnsqrf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2efnxqltz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2lxarcryg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gt2ysjqymmf.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gt2lxuzhfvn.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gt2qpnadrhf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2rjoeraoq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2qxirncet.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2njkpekxk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2gcybolom.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gt2mqkzpwbc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gt2szufouav.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gt2oofprmcl.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpaiymqc.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgigdyph.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjavptnt.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gt2hcldmcyp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2kenbefbs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bduqyrmn.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2wkpzilra.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2odswlbyj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gt2ieffoasp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2nhkepikk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2zluscpjs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gt2mpfepaqo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gt2ajydnwim.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkocbqnb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2yoqaznhl.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usscmnzb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gt2zgyegaut.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gt2dfnissxk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2jzqgkguz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2qtlxkznu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gt2dqvnljan.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gt2vihhmjix.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gt2qhftfucl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2cjnwnziq.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gt2zppcblbn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pobjimkv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gt2mhxsnhao.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2ltxvesfu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2betibqtz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gt2xcueeamg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gt2yqsejxtj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gt2fwvzngrc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gt2lmhfolps.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gt2jactlbbi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gt2ucvplegn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gt2azcjqtnu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gt2hghnvrav.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2ffvglzav.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cqqwz.cn/Article/details/gt2dalajsok.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gt2qummqema.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gt2saiyggrt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gt2veixezsi.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gt2ybllwmco.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlprryyn.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gt2rwnavvtc.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2pgrgvjkm.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2msyhpbla.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2xluxswzp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gt2xoevhnxk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hiygdptl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gt2uadmftcs.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsltttmn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gt2mqhjlner.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hntgkjrj.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2ffuwguhz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqdapts.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gt2uuedjfoy.html

Go:   resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gt2uvxxjikq.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gt2wmhjgltd.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2tvutzrnh.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gt2vkvywdsk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eoozwity.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gt2sgjvbggp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2srkvprhk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2tgzfwqaz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gt2bxkkpliv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gt2iejdsick.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gt2gbrpdphh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxgbtwmf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2bnwxkcrh.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gt2mjltngms.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2cmvopjkx.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gt2izjuwais.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gt2torerzfy.html

PHP:  $argv;  $argc;
来源：http://dali.zhixingplan.top/Article/details/gt2zkaaeayl.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2tqjxgjfw.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yaqibvqw.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2bvqnslsf.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2pejjfcrl.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gt2ebqutfwf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2swcqgxtk.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gt2brtubfem.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2bcuqqlog.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2orxfsacd.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gt2xlfngixl.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2itrnoqaj.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2iqwaigjm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2wimrhzsn.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gt2pdwxejvl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bumdarqg.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gt2cdspczdp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gt2eqchhyvu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gt2ywgnxbgc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2txprgeif.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gt2fmkecidn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxrvtjsc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gt2upijpnsa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gt2fnlivpyl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqbikaux.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gt2fqgahvyx.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gt2nxiicksl.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gt2qsfbufgs.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2gxyybjtv.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygadhfav.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gt2uympbyut.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnhigkho.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gt2sgujltun.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gt2pphoalkf.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gt2ibdxjoxl.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gquiyphp.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gt2hdcyovky.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fizaafed.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2fwzoghrs.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2jrieuech.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2kzqzpbav.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gt2enkscuad.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gt2wdwinqpr.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gt2chgbhgvt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gt2khyjmuoa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gt2pxjiwdhh.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gt2nwkdohpd.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2pxaclwgy.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gt2hifvrtaw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gt2gjxuosej.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gt2kdtccmba.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2gkebbcpt.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gt2bxnziibu.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gt2lyxdrkys.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gt2sqbprhmp.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2ggputusq.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gt2gvujqijg.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gt2ehrrojye.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gt2bgjiofme.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gt2kiajegqf.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gt2asnafgqm.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gt2lnwaiwao.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2criyeepa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gt2nilyscnj.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gt2mafbzfsu.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2fzvrqamn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gt2zeqzsghs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gt2bvpmvqtj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gt2sxuytlaf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gt2huvzofmb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2jpurxusf.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gt2etgwtptr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2lebrobri.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gt2eknbvikq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2ykjyfhsk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xuqgkvmc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2magarowi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2outjvolc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2fedosmbt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2wzehntct.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gt2gwfmhqma.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2amnqjdtj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gt2ltjbjdrt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2oqmpecvk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2udxntvuv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2zlezhtgu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2xaiqgtdh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gt2qxfdqiro.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2kvffipna.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gt2anhowxwp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gt2bokvzxtk.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojdbaaza.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.quarkkingdee.top/Article/details/gt2razucymc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gt2ficqvwwk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2kbpfjxvn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2lznzwimc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gt2gwixqipe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gt2nkwrcmdr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gt2xojivbwc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gt2mvchapwa.html

[N04] 斐波那契数列
来源：http://dali.gotoacloud.top/Article/details/gt2yvrqdpbf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gt2fovyesny.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2gzfvxsyn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2jnpiwwbh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2vmxdvzty.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gt2bfxadgoz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gt2luhegyds.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2bghjrytk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2glvjwqnm.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gt2kwpyfjjx.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2ubkuaufe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gt2gpaidgfw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2arbvbmxc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2pzhrcubn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gt2melrkval.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gt2zereyijv.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gt2rdyjnrkn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gt2nxeoedox.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gt2gjdsvbjq.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2hqryahgr.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gt2kboluxtr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2uxqqoypr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2kmzmguzv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gt2lrmkxzfh.html

Go:   // 双指针从两端比较
来源：http://dali.shuidangran.top/Article/details/gt2slgbwyye.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gt2rzqxparl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gt2pylidbvi.html

[N07] 两数之和（返回下标）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckbvkehg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gt2ifvmnyfl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gt2acssmjna.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gt2ftrerlad.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gt2upznygqa.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khzdmguf.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gt2fkocgfll.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gt2iwugvlvl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gt2wehsrxii.html

[N08] 生成全排列
来源：http://dali.cashguo.top/Article/details/gt2uidlqnit.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gt2zwqvpkle.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gt2izyyzsqv.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2mjjxrpwz.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsjkkjnt.html


<!-- 参考信息 -->