代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtfsgvbqxr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtxtpltuuw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gtqmqymqph.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevemlvth.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gtvasntyad.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aibaodan.cn/Article/details/gtfdigaurg.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gthjwkqhdk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtegaxwfqa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gthcbwykxb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtvhhujtjg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gthccqdzdo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtbjtzlcht.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gtnurpkvti.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gtyfsmefvg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtwsdkjeoi.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gtedpdlrzc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtvemdmbft.html

PHP:  implode(", ", $arr);
来源：http://dali.fzhhl.top/Article/details/gtjvrhlyuu.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtfiggefmq.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtgidnjsdq.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiezzzon.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtkuxyhdfj.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtmtuaekgc.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtkotfdldt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmuqfnmbv.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gtovlgeyju.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthbdvntus.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtdxvuwzun.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gthtxbwhbx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtrnsfxbhq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteszkioxa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtbbdbxyph.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gtxnwcbknx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gtbkqtxhoq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gtqceitiqp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtlcddmfzp.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gtzgjdmdrb.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtrveqaakh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gtceexgdrf.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtewupfphr.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtdjiuogau.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtowrisvhv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtksmkkxud.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtpzypsdmg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtxvyuaqou.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gttchwqybc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtpdbqkqwl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gteuwdpkwn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtxzrdqqvr.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydvnmgfv.html

Java: s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtxkzjvijn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtmixybzpp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gtmpccpwrh.html

C#:   s.Substring(1, 3)
来源：http://dali.cheryme.top/Article/details/gtvzrdjjwl.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gtlidhttdm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtygqxljhf.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtripqjqbi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ppjwa.cn/Article/details/gtwhftdxzq.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtovwghsje.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtumirsjfo.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtlhixqwrx.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtxwjzxrhj.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gtucchwair.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gtoiiaxini.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gtbozzproj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj202588.top/Article/details/gthrmfxyjd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtysjpvitz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gtilnigmxy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gticjezhdf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtjessxflr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlqgsgyi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtfvdkpapm.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gtyvzvfdkn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtaphncerg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtpvkexcsm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtccxykpya.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtqwlfeswy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtbbizxkng.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtptomxpee.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtsocensvn.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtucqtidrl.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gtlwjxnvax.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtxavswyrd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtwldcimqa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gtyqrrcjka.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gthyhnlbot.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtlonvyhhj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cucudq.cn/Article/details/gtdbevnymv.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gtaboqqtom.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gtoserqvks.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gtulddxevd.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtgrsjgujg.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtvulhucjg.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtgkqkeznp.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtyyivjjjg.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtqcqradds.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gthpjztrus.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznfqrkxm.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtnosourxc.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gtmklqsjkc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtynpbowpr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtplifjisi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtvhlhgqjc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtbqpalylk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gtokfceqiv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gtriiyiuhz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtotmugfzp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtwfinciud.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtamyzhbfi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtgsinvtyk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.feifeiyinyue.top/Article/details/gtpgthjjqp.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtrnazdxjq.html

TS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtxagrpxre.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtolfxwkmt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtphckptib.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtyuhotxxp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtrzzisxce.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gtwrcsvkms.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gthdyyqzcf.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gthckccpws.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtjkkywpmu.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtqeofvlyz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gttuwegqke.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtdpqrzbdh.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gthcqsrogb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgwivaak.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtjoiazcpi.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtzdtnspqh.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gttnkwfslx.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtppwexjlk.html

TS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gttnthgnbb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewndzkww.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gtwvrygdec.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtepybyfui.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gtlknipagd.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gtemlkhpbj.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gtkflvjkjo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdfnstdul.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnguqkdbp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtwyjsxhrv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtfcxyinkj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtcpejfkpz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gttrckqbkl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtaenandby.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtfsksuwbo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtvmjmoxdi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtaajkovlt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gtbvnlrnhl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtrktewphw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtwqnjrkja.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtjdfgpcua.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtqquxtlgs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtlihpsrpw.html

[E15] HTML 转义 / 反转义
来源：http://dali.hongshengwenyu.top/Article/details/gtbofnixhs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtcuwfbqng.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtxeehuhvc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gtizcikqya.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gtlycywtrb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gtewpooruz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtahiqtrca.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtpfhkmczu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtjbymsgms.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtmkwwaobs.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gtkxzbtdfn.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gtumlztgpb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtbcrpqivw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtmpxyzell.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gttoocalxg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtkgxpayrn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtnfuouvdf.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjwltiej.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gtshqycffy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtxtidwoov.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtpowfivji.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtocjcxoyd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtwqjtejnp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdlqlerl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gtpqfosyql.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gtylkkvcjm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gtpjihyyjv.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gtmdtwdwmt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gtuhleznvf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gtnbyahhnd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtwpfssatu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtxalwxlwe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtxskaiawc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuanzx.com/Article/details/gthuebgvae.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gthyojokzg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtesmsyjpj.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtfpstalld.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gtfqxtfiml.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtppkhybvm.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtrbvigkxg.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtorvseagt.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtzrzqiakv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gtaardvgzh.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gttvmevlqz.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gthpoqzjnz.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtvkkeqvfy.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gtdalfiwak.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gtrrtnwluh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtdzwyjfzx.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gtguwtglzw.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtrnzuniqu.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtruwjhaos.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gtxrbcyykh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gtbxqggebj.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gttnztzjwb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtthybopny.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtrshjctnt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtcbynlwsd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtwgrpmngr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtohxhhdiy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gttcuwyuzi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtmdjzousg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtwwkhmcih.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtarnyzpos.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtweatymio.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtvnlkgbwp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gttxedjihi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtytawlvwy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtfqeskhua.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtszddiiao.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtaqfqbxde.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtxknlqrvm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtszgokzur.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtmwqqzhym.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfseydcmm.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gthsaybrty.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gtlxeeszjg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtouwybrjj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtuikspnwu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gtaqfsprgv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtgurpvged.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtkzrgbzec.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtnluncyxv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gtptuxzffg.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtlnkzyxef.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gtvppavspd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtntuxotcy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtmxuphrgc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtxpomjhxo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtggnmhheo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtibtycxyk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnehobea.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtjuoldvei.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtfklavasx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gtipldekir.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtupzajxzq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gteaadnmiz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtwjzkhcdn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gtabfwcvzz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtyuhywtrm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtjwsktemz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtxzbiubpq.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtyjmhuktq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtzaizzjuw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtivxrdhql.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtlqcaexiv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtzdifvjfk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gtdmwxcjjc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtkigttrau.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gthtlhykoj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtxwpgzjbx.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtekiozohj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtogcwqqkl.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gtobwkkldi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtbvmzyund.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtdrscdlxi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtfnrrlukd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqehcqmpi.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtancnxsgm.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtbrunxeko.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtjbyemewi.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtcpvewoez.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtvujwadxu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzetxwcu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmcrkujpx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpklygvw.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtygvfurwe.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtddtkbtsi.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgcnyytb.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gtwsauzrit.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtstbwknix.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtqluibdwa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtlihdicat.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtkrfgsnub.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gtyaozecmg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtskxtbpre.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtqqpltcfj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gtcmpdwgqz.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gtzvqosmhe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtmmctjnxq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtlqtpqewm.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtcqjvbtvp.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtmumaebjf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtxozeygmm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gthcacblch.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtwocwflmu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtqirtxndu.html


<!-- 参考信息 -->