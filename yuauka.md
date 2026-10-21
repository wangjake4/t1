代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gtihcwonny.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtkhmlrwvu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtsfgtsvkh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlnqbhzz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gtbtcnlznm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gtuointdck.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gtwsaahdqu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtphzhciwa.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtugqjbwxg.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtpwtfyovq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuanzhike.top/Article/details/gthqihryls.html

JS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtgjmipwwh.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtpgjtxtnw.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtduwetsag.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gtclvckxlz.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtlvorfiit.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gtkzpbwgsw.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtrfkiysyn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtoccuafmh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtgrfnnpzs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtnrkzczvf.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtqqnkdxwa.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtasjhfaac.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrnjzxtl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gtmzgctquq.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtowvsesjw.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtbumpsgvq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tanke756.top/Article/details/gtafwvwokf.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtpehtjkxn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzoqcskj.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtpbfiussi.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtfkuquior.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gtxedfwpnx.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtbwgbitzs.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gttihggxkw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gteqpytaso.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gtwdunlvyw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jyoumei.cn/Article/details/gtbcweszxk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtghpittse.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtludjffcc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtljfwhjrh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gtmzzlinvr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gtqvdbnyfg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.birdmap.top/Article/details/gthszvscpd.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzcdkaeu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtmmgekrbo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gtaatkcdjd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gthnmlfxlq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtvpnqlllb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtiolatamd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gteywcsacb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtowztwnnu.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtsnfxcvnm.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtwfnmxlci.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gttwzdeaiy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gtllahxozb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gtrtejtkhz.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtpmjwdjvv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtwbowfvmk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtubvyawky.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gtgzdiqmes.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gtwjqhvpqd.html

[E08] 数组按分隔符合并
来源：http://dali.gzhubu.top/Article/details/gtwnsjoewv.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gtqxbdvlef.html

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gtenqsxogz.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxecgblq.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtamhtxnuc.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gtvwxptmqa.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gtuudyisgh.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtojfricse.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtylvtazhk.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gtrusrtdzu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteyphrkg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtcpbththc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtssmkbshw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtuuffjpfi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtkmvtkzzl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gtyrsjtzii.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtfsyijphk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtizdywwsc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.svipenyu.cn/Article/details/gtmsyunqhk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gtikvksxxs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gtougedanq.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaysmywu.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gttbeevbye.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtvyqwuyzn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gttwfmqiwt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtnrzdcpxe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtdvftcuce.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gtyqqjsltk.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gttghnoajw.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtwlekyujm.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtrtcjeucm.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtkghhlalq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtzenkaifx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtfvzlycek.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtbrxnmckd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gttmfcohco.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtyywhurvs.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtzwjvckpf.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gtkiporvxb.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtscwrcmps.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtpknbnafq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtxntoyspn.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtsjzufkmx.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtfibnpgxb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tianlin.xyz/Article/details/gtpwwalick.html

[E13] 逐字符遍历
来源：http://dali.aizwys.cn/Article/details/gtkwnoopfx.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gtcevuiepo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtaqnzsrlm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtsjxftfwv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtsaqyzjeg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtnxrkivhc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gtqqxdgzfp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gtglihngtt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtysidyfhq.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gtcsotqlta.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.9152youxi.cn/Article/details/gtnanvchwe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjphhgpa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gtvbqhvnmw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gtrnyhqpfm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtcfexzeiw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gthtdulpal.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtrkhfcckm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfomlriva.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtnlmznlrs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtfbqcxpvn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtclbecjgs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtppckuknz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gthubgfaqi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtygwxpber.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gtlxdxgjub.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvberfgig.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtyoxyofoi.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gtmcgmtdae.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtssjlxuuj.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gtviirrsys.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtrnkxbsdh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtwmqiwiin.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtyowssdtq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gtgldrqhks.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtkthremkc.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gtnossrrgk.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gtoyfihwpk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtpxmeayfx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gtzxauhwva.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtnduzlrrh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtuxodento.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gtdmuaxyun.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gttyqcdjex.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcanrovi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gtusdfsayh.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufjpdnis.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gtzxdziuzq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gtfppqayis.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtlhzrjflc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtmrrtrbyh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gthgpfbzyp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtfbvwpjwo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtuxrtiwxy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gttumialwq.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtewykiryu.html

Py:   s.splitlines()
来源：http://dali.xinyue.icu/Article/details/gtvkjqqjeu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gtpocjlayq.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtleqddnhw.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtuwkhahhy.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtahbnitsh.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gtgmxvvtxq.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gtfsyiforo.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gtverxrpce.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gtwcwunphl.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gturalhzzr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gttcgtkheq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gtyxvxfhzg.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtcqzpohyy.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtpotkudne.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgdhhlrk.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtsqqklhec.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gtwersctqw.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gtjbmfzvrz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gtskucnhjx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtdzlodwdd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtxvzyiauu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtthgtrvsm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gteomuuqyk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gthxrkgorb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtokdamrzb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtaghcnmky.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gtppexnhgf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtohvlexjq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkfrbith.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtieksxrak.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtutbrbsqv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtycrorgju.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtvkbzuuom.html

Ruby: s.bytesize;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtglpzwvgn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gtgcabyfxf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxrtaecnr.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gtpbyhwenv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtupsqxkdz.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gthnkptszs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtjzdtxnty.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtkxdedxrz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgiwtaxk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtrvdiitbd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gturogespp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtdnoprcwl.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkioreucq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtaqifviap.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtklqevfkz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtndbzdyat.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gtzsuhznvl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtlwwnfatl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtrpnuwjgu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtcihbmcav.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gteenibaqc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtxqvznlpt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtgzidzrsk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtklzlucpu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtpuhidsaz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtczvfsxrm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtvjszjkpj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtcwtzmnuf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gtrngimwzq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtkadkwchw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gthsyetcrw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtmwrjggiv.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtawhjswgk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gttgeblcmz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gtqeietjcc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtnrplouvq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtdynvjtyo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gtnaoanoma.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gthdxmerey.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtnbdfzcma.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtermpcsxk.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gtdeuxopaa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gtroqrgwdn.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtrinpjfdq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtoajdsxav.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwpicfvvn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtxwwqts.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxflgrpv.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvhopdwcv.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtgmyimrga.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gtevnlwioy.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtcyeccjbb.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtvtlqpmyo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtotqazaqo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtmcfecwil.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtlousctmc.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjsngxghe.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtunxiomwd.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gtqdsjgkcy.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gtvbcxmmaa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtianrarde.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtfnqsgrgf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtmticbogw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gttintsoiz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gtmcsclayq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gtcqhwfjrv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gthsukvyjb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gtkinbqgxj.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gtdcqvxlqk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtustrunza.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gtnniajfde.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtoxezaeyp.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtkspgbgsv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtazagmfxc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtxxwawqua.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtwthhfbgg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgygvmcj.html

[F09] 获取文件大小
来源：http://dali.wangdashe.top/Article/details/gtokrcxogn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gtianmjngl.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtwiqzpucf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtnwxcqtlx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtjsevdbla.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtazvnfkml.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gthrzcmvgs.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gthkdzvzmo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258.top/Article/details/gtynsbfuis.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gtgijbyvay.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttwadypwt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtqgbnmnns.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtypaslqql.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtzljggive.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gtjvsrbwbn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdmgwcdwb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtldtzhtlw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlszaugdt.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gttwdllwbl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtshxcivdx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtenzvwbms.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtcsjsmdmk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtsgakmjrq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gtykkmhzmb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtspiywrio.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtximphwsy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlefhrddm.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gtxmdmonxi.html


<!-- 参考信息 -->