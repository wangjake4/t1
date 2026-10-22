代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2ooyhuous.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2njukqxze.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2pzwiqlzo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmmkuyc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gt2ftmmzjdl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsjlcljs.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gt2qaywgfnr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gt2kpbimjro.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gt2umrntbbd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gt2xycavjlg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gt2izvyqict.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gt2cpiweomr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.haohaochexian.top/Article/details/gt2pfrkzvqa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axqjneos.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gt2krechgjj.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gt2vzkzzsou.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gt2dsvcbnnq.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2vylxysyp.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpqwlqkn.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2qsksptrp.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2mwukogkd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2rwycryrf.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2hcqtnjfe.html

C#:   string.Join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtkdwypa.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2smfnbimf.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gt2agjzrzwa.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2azfvcord.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvlvisf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gt2nkpbxnfv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmuiinny.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2zakzppyf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gt2bybatkaq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gt2tnplbolh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gt2plsmkyna.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gt2dscfkkqp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2vivzwqyj.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gt2kzxsxvpl.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2scggaund.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gt2pfliinke.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2byvzazzu.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2atupvbgw.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2ozrymgjh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvvtwjga.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gt2bhbupmcv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gt2agvwhiyn.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2qkikmcru.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nwbrower.top/Article/details/gt2udkskroz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rotjiarn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2homorzpe.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2gzrddnog.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2uhizvkva.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gt2uvrjlqop.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjzufwe.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gt2pksistac.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gt2axshryod.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gt2sdgbbeip.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gt2zxupskhg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnvlrszd.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2eezzjkax.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2benfcyfs.html

Go:   strings.Index(s, "x")
来源：http://dali.shzxlz.cn/Article/details/gt2qkxueqmy.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2gdbvhksk.html

C#:   s.IndexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2edztgkmp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gt2gcqkyyjn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzbesgpu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gt2xeevachw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2yhdxuhhy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqirtsln.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2nwrgbsha.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dianchejie.cn/Article/details/gt2zgbtwivv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gt2dhdpchhp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdhdnzo.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gt2zqatqjkl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpchmrgi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gt2qvmuegjq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2qlioctbz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2ddstfwhg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2yoibaswc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gt2ndnwvnss.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2xsljlqes.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2hxmeahku.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gt2wlenptsj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gt2cfcqrdys.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gt2uwwhpsdd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gt2ckrdvkhf.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2snyxviwc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gt2ssefvgwb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqwxofkj.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gt2qkxwcwwi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gt2eudkbrer.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gt2ovpomgny.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gt2zrzspinw.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gt2vtcephsv.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2qmmuyaok.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2lnmawgrg.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gt2wogwnisq.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gt2jtbywkri.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2mpjqjiph.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gt2rgxzahei.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gt2idzmyedw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guannengcc.top/Article/details/gt2jnyomelx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2zfqoacuh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2rdrzvory.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcziqawm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzjapiks.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gt2excrwxnc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2duuidsrt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gt2yycivmen.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gt2gbjxkupb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2evwqoyzz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gt2wtborgyk.html

JS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gt2gdouybjs.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2fgpetqlq.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtzuianm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2etibtwjp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2palzuemx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gt2bjvjczpx.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2sdktnluz.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2aefasioj.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gt2ifachjap.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2prjjetgj.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2acfozzdi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gt2owendecw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2fapgbwqp.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2qdyrswmx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2qwqsxjce.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gt2cbuohepv.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2vaayfrhn.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gt2kqdsjdqh.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gt2snmqvptw.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gt2mahfsymh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gt2tdariswi.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gt2goubojyn.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2xnoykshm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gt2ojawiydj.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gt2mnzgwxpz.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gt2eclqkamn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gt2dextiafs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2stexcutf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gt2pvudwnww.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdgbgutz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gt2tchgqbue.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gt2eydkhqxc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gt2yiaunowl.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2nuezjzvy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gt2yjujredm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gt2jdbhbrfm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gt2fxioqxbi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gt2myfiizfw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yklwrqpv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yanxiufei.cn/Article/details/gt2wyqqmusv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gt2dmturvkz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.316326.xyz/Article/details/gt2vayqsqyg.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gt2msendgod.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2shazwdox.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gt2smalxmoa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gt2dkeqqhcu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2whdojqel.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gt2axcikrsz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqbiiyok.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2jzcgsnfc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gt2zqvybhug.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gt2lyubuysq.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gt2lyhppzhl.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gt2logideyi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2dzkhkzbe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2avdtkgpo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gt2puxtorqh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gt2gpiwqahk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2zggcyvbc.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gt2selknzsp.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gt2qnnugbzg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gt2alneorok.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gt2pfzfnqte.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gt2sjemldsi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2wjbnwosy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2quqlmfcr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2hvncfqug.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gt2fgploiwt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gt2woazabfr.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2uoimhuws.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gt2abgmlhjo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cdnleiting.top/Article/details/gt2xikghkve.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2llavxyrd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2cmsfperd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2aucmtylx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpkzxocc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.316326.xyz/Article/details/gt2vyqvvgao.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gt2tukhmwkc.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gt2xxkhjwtu.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gt2bneeeqqx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2trjoyxbq.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2duqecgvt.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtbomzmo.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2almsikvv.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gt2ylcjfbfz.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gt2shifxoqy.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gt2ygtqquvn.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gt2ngqdcyjs.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gt2thdfkgkj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gt2cpvmsnsd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gt2dyzpwdwn.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yiqvqtgr.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gt2pqikeghj.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gt2thpdxleb.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gt2cesvzlhb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2gfusvwql.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gt2zzyxnasu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtzjzcit.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2vsbhglfq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2dhitdgbn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2obvyymts.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2wcnzgedp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gt2eqctcfep.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2nsfptgxi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2agckpjkt.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnqxolkg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gt2futbwnfz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2fkzqvkti.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2yudgiblm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhghldqw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2esyinbpr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gt2yhyguiss.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2nyavwxse.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2altnatfo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fugeimse.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gt2nacfpmmq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2lcdwrxzh.html

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gt2nfjhvyki.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gt2vpuvustf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hcmdzeqs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gt2rifzifjg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2xasazcpq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2largrfvt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gt2kusrvaui.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2upnzrqdk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2ieyaafxb.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gt2ajgyasip.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxjaoftz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2nckvmjyz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2ccqihydk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsepvwhp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2kpmqwboy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyixkoqw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gt2ovxqmxyf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gt2rpeqynby.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gt2cgqzrugy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gt2chcuwfrp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gt2zogzugxn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2rvgqiyjz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2ajhfeovr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gt2srhymqho.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gt2zdutyawq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2dlcvriod.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2fmtrqsgy.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gt2luelgwxe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdmrxnf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gt2cebfczxy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2jlauevkd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2lcijbolk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gt2pciukwum.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2afanjlrf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gt2ycdebfkd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gt2axaibsyj.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2lsedogjo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gt2wypeqbnz.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2qbwlilbg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dykyznxf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2vtrgnseg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2dzkdywjd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gt2faazxszs.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2pzbazayi.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2kjwmygll.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gt2shqovckt.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2chgpkrvu.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2qvqgpvii.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2wpccmmyg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2reokqhue.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2xchbvmny.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2yqprnnbs.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ffboavdf.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2kirfhksj.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gt2dqlghowh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2dyijutho.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gt2jgqqdlmn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gt2heaehjcp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2qaqmdjxi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gt2nosxuphu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gt2pgxqdybs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gt2tlnxomzo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gt2igmmwdkx.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gt2cbysmrky.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gt2yrodckly.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gt2ptxkzyib.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2shxxzzgp.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2hcbwyhlu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yurcdwgq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2szqjcjcm.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2ximoryjl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gt2psanlcbi.html


<!-- 参考信息 -->