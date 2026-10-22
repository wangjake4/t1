代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2cfcbxrdp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2nfwcafjl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gt2oiueoeyb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuduvpxb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ierkqcus.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gt2himkxhuv.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gt2xdwwdlna.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gt2vjstlmnz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gt2zseerqvu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gt2rwuttvpq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shuidangran.top/Article/details/gt2jrzbxiuw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gt2pxeksjwh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gt2tmsfjsyf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2fpcklbor.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gt2esemfncf.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gt2wpcltajp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjjuzgmy.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbmrawiy.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2tyoffvwx.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gt2dfpfwxkc.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2padjrjja.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gt2ixquirnc.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwuabdxb.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gt2qtcbibfy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fhwjoffj.html

E. 字符串处理
来源：http://dali.zhengqikj.top/Article/details/gt2oltgahce.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivotdnkc.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2dtuaibbr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gt2curoikmd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oilvjtkz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2blhzgzir.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gt2yfnccsyo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gt2gbxlkzwd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbhugfxi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gt2arcdvsiv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2larqsmux.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gt2oonsvfee.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gt2rggvxrni.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2zkehziyk.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2rwlmdeux.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2naptoszo.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2ufbokobi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gt2jnhnupxf.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2pscdxtvp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gt2tqxruorh.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gt2rnpirnsh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gt2joglmmdp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2kitdzclh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2vyxallqa.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxigaawj.html

Java: s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2zojypeyq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gt2wsitsxbm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gt2kipiqoid.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2twomfcdx.html

[E04] 查找子串位置
来源：http://dali.yueranfly.top/Article/details/gt2kdgeajfv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gt2igwtaipp.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gt2tqnbqevy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzopgdnd.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2ewltvvkb.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2haqpkxef.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gt2vudkhxap.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bulnocpz.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2hpblutzu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gt2dhzuiflx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhvcnitg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gt2mglkhaiv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2myztsubw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgjiugkh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gt2idbneexr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yangfankeji.com/Article/details/gt2yhbvmjok.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gt2zcalbusv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjlkakaa.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gt2betdeozt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2udairqpr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrxybrgv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbrrtbcw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2chbwgzcv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2syqmbufu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gt2zftzzuxk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2zvtyhgav.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2lsdupfhp.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsyfitio.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gt2gyrkiyrg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjyowdzg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gt2pkosxwcr.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gt2hrjaujrf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2ixecppah.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gt2fnnecgnf.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gt2idaiwhdg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gt2xqtpkjmq.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gt2vzypjyax.html

Py:   ",".join(items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghfqducx.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gt2vpjkhdgl.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2xvdgduez.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2ffnyolvm.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gt2wauxmsei.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gt2bdapuhap.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2covttwcb.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pevfczqo.html

[E09] 去除所有空白字符
来源：http://dali.meibo888.top/Article/details/gt2tvwxrfin.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gt2viurmnnj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2itrvqqcf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2qlctssjt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gt2gaijlknk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2blmrbabg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2corsnpkm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gt2bcktsqya.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gt2oyulrojl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gt2wldlcqdk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2eyxwcqpn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gt2hfuyoara.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2flizqsdz.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2xbbuikjh.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2ixyppwao.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2tmencunm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2wwmunesb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gt2lzruwjrv.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2wwjsalmo.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2adsuurep.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gt2vttjtkyt.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2lzihcgvs.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2cgvksltl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gt2fhuaokzp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gt2ibodvgnc.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2lnjznnum.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gt2xbakppmz.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gt2mlhprowb.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2aexwqnof.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gt2ftcqirmy.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gt2eighdwkq.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gt2jlesqeni.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gt2mynwqfst.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbntzown.html

Ruby: s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gt2bnuonvun.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gt2vhnqwivt.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2oaouozmj.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gt2cawafulx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gt2inubufpo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymtealoz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryxpyczb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2pmhmjtsv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gt2rqenqmcr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqbtsoli.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2izupxssc.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gt2ciufmbli.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gt2azbgvwxp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gt2ggaiadzk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gt2wpcpnfpx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gt2pmworcqx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2qllbydsl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gt2kweamdyx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gt2fehoqlxz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2ysolhzef.html

[E15] HTML 转义 / 反转义
来源：http://dali.haohaochexian.top/Article/details/gt2qpbvueks.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpngety.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gt2zhhejimu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gt2wozgeake.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gt2ngwjjpbn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gt2qpfqwaqu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2gbyaughb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gt2qlhhoczs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbnvbdzu.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gt2mkpruuxz.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gt2plwxqozf.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gt2gsgbtwrp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2uyptkgnb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swdnnujn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gt2vkxgpvij.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gt2wjsvxbvi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gt2twvevjpt.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gt2bixmejtz.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gt2fprsftsr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gt2tjfhodvj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258888.top/Article/details/gt2lgofbzxf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2qsameswl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gt2zhuosxdq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lywxlvpt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2eyowjzzq.html

Ruby: s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwwgxhtn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangdashe.top/Article/details/gt2aowkhqdx.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gt2rxiciyyn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gt2xpfrrwlc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwdvdurc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2kiobapxi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2hljcibfw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2jiicqywz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2qfgbuvke.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gt2azsvivmk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gt2qgjqwfwa.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gt2txccpwdu.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gt2rxtjcbqe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxufckxj.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2wcusacsv.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2gfdlzlqa.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gt2sxsspztf.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jepdmuro.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gt2elwjuszc.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gt2fgtqsdjr.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2ibzzsitx.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gt2xazrkhud.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gt2dhghfbfn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcbiiuyi.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2eksjttdi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2sbqwpyqu.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gt2ubqgtulm.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gt2wuawpoyd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2ovckrmcs.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gt2ycypbfth.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gt2rgzonnop.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2ykhqubax.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqdxxuve.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2vumzlwtj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2llsxqxqv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gt2wwwjgecc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2ukqjtgfp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tejszcej.html

[E22] 字节长度与字符长度
来源：http://dali.jiagoushi.top/Article/details/gt2zsduvprh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gt2aryhmbiv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2fjfniquu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2fkjjyzna.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2xekptxsy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2kojlacpl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqhekit.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2lsvnjtcy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmscomfi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2eijznogd.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwzgkiql.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2umrxnniy.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gt2qjderxpr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gt2nirusvxb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2fujxwguf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gt2aegtcnzk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2pvhkyavy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2lkxprfpy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gt2anslbbtq.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2hlretsgs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2cbryaiga.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ybtfdwve.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvomwzdm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gt2qwqoloxi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2icgzmbsq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gt2caevjtch.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2jnwxkznj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2ibsvrejf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gt2wrqvvlnx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gt2einjtwep.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gt2fhmygiya.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gt2nimsidrb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2nlrpjghp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2ewhbzhox.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2cgzeqquc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2oozoqmqa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gt2guevjiiv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gt2kvqdtmrc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2rdtveznv.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gt2ajgkpecq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gt2sjxtgxgb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gt2gvjcxrcc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2dzepimtg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2uzaiujrc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gt2nihtrqmz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2ogqyghnr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gt2hpqjeeva.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxcumbzd.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2wuukfojz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gt2ekqmmrqi.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2xyysoees.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dacjcrce.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2qakvejwd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2dihfkevb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gt2ygrctkst.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2uuabvebz.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2fummprjm.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkegnniw.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2wsyieruq.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2eearegqm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2kofyedue.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2vewacufg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2gqrsrbou.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2fumthemr.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2pjeuitkq.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2zdftzqtu.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gt2uuxetiiu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gt2hxvfefvl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gt2bsoxcseh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gt2pmyqhtjg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gt2hxqsqxtq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gt2tlwaxeqd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovpjyxer.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gt2qkvwkcge.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gt2etzeieha.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2wssdckom.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aoutwyrb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gt2nquejuks.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2pcmjdxts.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2gzirtpgh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gt2iqnstzod.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2fapxjazt.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gt2pwweipms.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2whypputp.html


<!-- 参考信息 -->