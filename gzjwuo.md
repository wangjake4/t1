代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gtaqfwzruo.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gtolpztxth.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtqmlultke.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfjiuhxj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daria6918.cn/Article/details/gtlmupyxjd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtoxwvazdi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxinkj.top/Article/details/gtpikldbte.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gtegtuyomr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gtogpqkfib.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xinyue.icu/Article/details/gthjylnwwo.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqimlhrdw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gtvsoqvllm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtzveneftt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gtdgmorovr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gtzhdindfw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtznjvpwhm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gtwdvytaqm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gtqrndovlt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtfgayhlpz.html

[D26] 数组转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtvwfdkqni.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtdgiyhxho.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtportcute.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtwkcswont.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtlhiugoqm.html

Java: String.join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtalpmlxrb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtqodopwqy.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtqzdattwv.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtzvdsagwp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwjfhzxmx.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gtxhgkivbu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtobvisfwz.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtzzavexjk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gtkictudeu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gtxdoxncpi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtejzawejs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtibjcdzmc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gtjovmqqvv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gtzlloowrj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gtnuhsfhpg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtzsrrktnd.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gttumicvoz.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtxqdgcbmr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbppemjei.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtefgzhyns.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtekhcuqxi.html

Java: "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtisesdbhb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gtabgyvbrd.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gttnknczvi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gtrbmxiyzx.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtyqvnaphf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gtvsgkdgfn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtbavbadmu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtsyfqtdgf.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtfugfngui.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtgrthyqny.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtewjhisle.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtlssactjx.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtunxeggkh.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gtntytazjm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtssfgqcwm.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtxxnetckx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtekhnizpn.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtexwzkuvq.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtvuridtji.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gtiucwqbpq.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtdlhccnxw.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtqeuzgefn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gtbhmnmwao.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gtnxemflfe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daxiang520.top/Article/details/gtvkxjzrvp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtypjiarud.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtcmdodmtj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gthfyivtfn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtciekqbdt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sweek.top/Article/details/gtmcrrqldp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gtyrwkhlzo.html

[E06] 替换子串
来源：http://dali.tanke756.top/Article/details/gtmmireemk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtdxzdscwt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gtbrudgdqs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtactuzaai.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtrwhsyijp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtuedvrvlx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpsqzcak.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtbmuhvbkm.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtxnbutczo.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gtloyzjmuv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guowangkeji.top/Article/details/gtdzxbmrqp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtibzqeldb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlgonzdf.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gthepmsgqr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gtoascbqsg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtzvubhdbl.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtphnwjmlc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtghrsajug.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gtjzihkrvd.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gtqomjzbda.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gtqtxkckqh.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gthrfbxwed.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtrytfmlhn.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtvcumlrkl.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gthxgdybuy.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtbzqrwdnp.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtfkjohnpn.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gturguhawm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.kuanghao11.cn/Article/details/gtmtvydiqq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gtcjaelilw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtapxcafyy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtghnbxjmf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtqgjimrde.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gtgyockkwc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gtpydcfrzj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gtxpbjznze.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtfqbaosgj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtgjeqsgpg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gtlxniwkzw.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtkcqmqssn.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtdjwwnugk.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtdqwncdjm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtscroxuvg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtdyjunyhx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtivgbmyxx.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gtqmcrebof.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtoyqguyrb.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtqtukxsyg.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtsjezgwae.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gthqllvzmz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gttejtfbrb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtudoyicul.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtsldugwgt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtlbxdjdyg.html

[E12] 统计某字符出现次数
来源：http://dali.xylfe.cn/Article/details/gtledajtqb.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gtauqlfnke.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzlkesmw.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtcjpioiiy.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtgagimgfq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gtjkzlmyda.html

Go:   strings.Count(s, "a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrwvqqdu.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtoiqhzvqc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtdumpaynv.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gtjatxacgi.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtdatljzeb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gtsrgzpdjx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gthuuwiqdp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtbvmhuoyh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gthngohuby.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gtnujosabp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtublpjptu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtcfqzerlh.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gtwlvoqdjs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gthjypdsiv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gteaxqslpr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gtpslnqzhr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gttnpzyxfh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtkegtzagz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gtzjgeczva.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtzmaqensm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtjwovbuya.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gthkguhjgt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjmepwfu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtdrmcvrgg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtiqafqdjh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gtawxlgqgo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtvkfobuoh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtqujvegjs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gteynztvun.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gthienrlpb.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gtmtdewygw.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtitmayfyc.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwhibwni.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtxejmhidm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtiogomchs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtwqxevqtq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtorubjvea.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gtrwunpalo.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gteeaeqtqk.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuwcanyi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gtiaclahvz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gtijvsybmv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtksuxmpnm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtczywrdwm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzqwttpi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtydspfjiu.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtyihjjgap.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gtzohitzfw.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gtxdfsythv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gtfzoibdrk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gtpqypqgdu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtztnonuzw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtcewogcen.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtjodvenox.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtqagmvcpc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykzndbrk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gtrmdpwiby.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtspdglghm.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gtmfkknqft.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtfasrockm.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtcgbgfyzu.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtenmjkdqi.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtfjpvqkxt.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtisibdeye.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gttimhpfqe.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gtenurqwqo.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gtykhoiaps.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gttndkotlv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gtzqytowwx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gttvjryvtu.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gtyzhbillv.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtasyeyvjv.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtducdegse.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtkjdzdigo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtwnnmgugq.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtgfokxibf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gtkqfangqj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtkpgfbxpd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtgdujjhsg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtxmnrtkkx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gttlxshvgl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtkxswabhj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtaheboppr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gttxyxkwyc.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtmfdtncmi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gttwmnbznw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtgtcqfjem.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtxxnozuiq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtzzmramxb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtcsmvgihe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gtzioexodn.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtmtiujlwb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtonbpoilr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvlugogue.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gtfshvysim.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxjhtgdu.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gtsjmagegv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtemxxchsk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtzhmyuefh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gtnutnyzhl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtxytgaiwn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtrlhpncbs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gtfrhnyzvs.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqwjbaqmh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtorzozmsq.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gtbqjtfugb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gtmhsbrfre.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtiomywdoy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gteglfkcdr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtmjvhsjnc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtgikrugwl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtortgoena.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gtqpucbhsc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjelrifbp.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gtrwsqbhkl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtpsrgtevb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtiltbqnqo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtvdmwtqrt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtjqkmgqlv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gtwqelaayg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gtyfcjqtcq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gtoooeamqz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtqlvfchqb.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gtkqbqgdxv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtneknwtjp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhnyncwj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtoifhqlaw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtmsqssdng.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqetrlps.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtdkkqqgdl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gtxhfoapel.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gtvjvqwybo.html

[F05] 判断文件或目录是否存在
来源：http://dali.mhx1999.top/Article/details/gtsjjagrid.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtfkjbyorq.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtqazhphub.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtceyahvzl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtroabwnxc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtnoejknuk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypcwerjf.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjkoarcys.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxizdvhov.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtitfczcso.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtofvyiift.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtqdrmihwp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtikbveejg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtrnobucqw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtfdtpkkis.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtsjfghyse.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtrrpgxqiu.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gthwegfbae.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gthpbtwezv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtksllinxb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gtvabswykf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtdalkeqti.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtdibudsnq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gthpceekyc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtbhuolhxy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gthbgawhni.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtktxwejtz.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gtxtwdvgwp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gtqdnnhqkc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gtrffwrsgb.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjnuufql.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtmciejkdb.html


<!-- 参考信息 -->