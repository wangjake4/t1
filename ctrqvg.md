代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtatkxcfhs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtpiqriuec.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gtzjiiiobo.html

[D26] 数组转字符串
来源：http://dali.hfpthk.cn/Article/details/gtwxqdcsfs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtkoqkiogo.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtlrrkdhav.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtfcznqrwz.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtxodvudus.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtavsfqtua.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsulmlcfc.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtogmzuyso.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtkfdqlxvn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwlbtknfm.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtvlvrwnfz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtchwtzfbg.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtgshqllhk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gtjaccdvft.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtefigrswf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtvutriwxm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtqjqxmlmh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtvehnfull.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gtbsgzlalx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gtxycrcqks.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtghtsftqa.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gtpbdulikr.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtcvbnnssb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gtjwlrujvu.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtipgkkspv.html

TS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtebaoveaf.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtzenyugmg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtbkmtsgph.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtkppzrxut.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtymyvaomn.html

[E03] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtcfpvvzqj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhixingplan.top/Article/details/gtqlsvwkio.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtzuvwbudb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gthkrlegxo.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtnkxxiaeb.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtvmtoetfw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtceybejdh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.svipenyu.cn/Article/details/gtrvhtyhle.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gtemxothmo.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gthiwuwbud.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtxusikllw.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gtiobypaew.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gtibbzhzpb.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtpjssdyuw.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtzfgswmmi.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtxzlzuuxf.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtsmlleaxz.html

C#:   s.IndexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtqbfnfpxg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.meibo888.top/Article/details/gthfhkxcmd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gtyswyddyb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtyymxvlbo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtgdmioyuf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gtnoagboel.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtcyfsjohd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gtuifjbzji.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hywenlv.cn/Article/details/gtommmsqwv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtqzcntqfy.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtxctfveuj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnrshlpj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsjkhzhj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtkhxmfgwb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtnfpmzukj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtfpmxgvsq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gthxjvgnrs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtihkbtqdf.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtubwnhzrw.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gtkybxsmnm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtjziapvqd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtfbqmqiyp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gticpuncft.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gtwgbfttft.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtjjitjcaj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gtihzwipzm.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gtvcqimnpt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gttpvmauwb.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gtqrteivpq.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gtvpyrzcgz.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gtifksvgof.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtoecxngjn.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtujfaiqfl.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtbovjgdmr.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtqimjlbnd.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gttwatzyoa.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtqnymmmhf.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxpjjofk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yangfankeji.com/Article/details/gtfuklmzhv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtmxkxlsjh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtolsbydxu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtwtarrqmg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtygfqhsks.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gtdvqigvzx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuanzx.com/Article/details/gtzixezqqv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtfmbhvuiz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtremtljww.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gtedslphmc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gtqqcsmwet.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtkjxgdwzv.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtbjiyyusb.html

Java: String.format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtahlcnuww.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtmvwwkvjq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtdxvftgsq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gttklgeain.html

[E11] 反转字符串
来源：http://dali.svipenyu.cn/Article/details/gtmsjxtcgn.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtakawottv.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtfwrwtrrt.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtysgpmjyc.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxtlwvyd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gthgtyueok.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gtbfhzdhxk.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gtokavffti.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtzhcntghx.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gtjzzvuxtr.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtrxgabeyh.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtizssvaar.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtcccckwbt.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtuyyyanhp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gttjbvqpuz.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtzbwwridn.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtoqejirxy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtrrjpupar.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtqeuoxinv.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gtxmojfptn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlrvxeheu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtfhvkkuqm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcizbsbuz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gthseoozob.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtnfuvfkpb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gtxtchgxmd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuxming.cn/Article/details/gtiwzhxuon.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gtjjdtcjmt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shangyingyoupin.top/Article/details/gtypkogoan.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtltpwayea.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gtmvzgnqds.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtaoytcvbq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtyrxmpbdu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gtnmdmkrfx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gtktkqepls.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvtkqokn.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gtriabpoer.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpgorxsah.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gtfhnqtbjd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtgghhevli.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtapgxijkb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gtbtygemvh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqecqwmc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtxlxkcgng.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtgfzecpug.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtclznlmmf.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gtwezojohq.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gtnhmnggfw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrbqierd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtvyznnbmi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gtdwffqaaz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gttmagnaef.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtwdiwcqak.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gthzgvrmgq.html

[E17] 首字母大写
来源：http://dali.xziqi.cn/Article/details/gtnydktntl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtumtuudkt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtsbzxjpza.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtrqhelsej.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtmyvggrsw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gtegjlxmws.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gtvfzssmrm.html

Ruby: s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtozlmewbc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gtrhqcrnnk.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gtyigusaqt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtpugsgqup.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtwnwwhbtj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuavzkjs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtdoyiucqd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtjdbnjjwh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtpswlmzad.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhixingplan.top/Article/details/gtyixximqq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtljhjkpiw.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gtwicrouka.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtxijlvaza.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtedkzwkkk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtvalwytoq.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtdbthwktb.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gtossqtlle.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtkluwsnso.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtiomongiu.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqmabvci.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtmgbyohen.html

Py:   if not s:
来源：http://dali.daxiang520.top/Article/details/gtibbbinvz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gtketkoqgu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtoqzgpfon.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gtzolgowrx.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtdtbiqcls.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gtaxivdraa.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtrgwbnrrj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gttsiusdpu.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gtlzlaikgh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtnruayrql.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtcoypyjfb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtfpqvdqpr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gthpyxzcnm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtpaqzfqgr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gtwqvcjslo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtlabfffwc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtcizlrklt.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtzbsermxi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtrlasffnv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gthyrtauit.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gthwwokuvw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtmjgtngut.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gtnzhavtwa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtgyypkqtc.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtkquwznsk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gtriywthqt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthaqnplkk.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gtqcmzgnmj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtphrpofrh.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gthhwgkotj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtcorcejbx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtsauinwyj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gtbiblizyd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gtxwzljraa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtiujxkhzv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gtrsuhoobc.html

Ruby: File.read("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtamruosue.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhreyyfr.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gtssuihuml.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtyrlmswms.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtcwyojdkb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtbyhdgpir.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtncqomkuh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtxyleworx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gtqatgdaan.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtjrlonxes.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gttxgcgsqd.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gtponphwqw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtouuyqmbt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtgxrdtgmr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gttjxxhmis.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtszbihkhu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtxcpfkmln.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gtzswxivci.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258888.top/Article/details/gtsagkqiph.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtuffqbgsg.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtllflgjsj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gtemafpgwz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gtfdvjzjgb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqjgecmm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtpxwqdgwf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gtnarowzbc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtqpjpsrpu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtvkkxwaxm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gtfkpdbozc.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtdjthajjs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtsrqjmppg.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtwdwdkghv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtsjhqmhse.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtfejrgwxf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtdsdtmozf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gtyuwmabyv.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtrgimghkp.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtvsxgsxos.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtwmltjhww.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtiffzlfkm.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtcuahhrpo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttmwgmksn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqbrulljr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtsurvwfyv.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtyuroiyte.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gthaqsfmuw.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gtaithecla.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gtiqlzidie.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtgueyxifd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gtiffebpkx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtqgufpqhv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gttpgtckqn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtekarlziz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtfdntdtyw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gtpmlmjygc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtxdfkoooz.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtpjzbricx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtqeyhinxr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtcpnbyfwn.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtcphcxtsq.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtkymmuoul.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtrsfnpljf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtqzielxdm.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gtfsmcmxto.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtzkmfdntd.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtqfecschk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtcwxdgoyw.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtmojmccur.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtgbpazofj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtifdhctsm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtmkgkvulg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gtgyyqqqco.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtzrridhng.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gtgvvgnfib.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtncfuptfm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtfobvlinn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtyuvyvcob.html


<!-- 参考信息 -->