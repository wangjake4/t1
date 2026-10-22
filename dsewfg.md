代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtimmuliti.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtmrfrctrq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtxvbyukmo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuhnswfx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gtiwuwkocf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtznrtjygo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgfzy.top/Article/details/gtmcbnqzvb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gteogjsfch.html

[E02] 重复字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbdbxrko.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtvtbbbpmc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gtlhswqqzi.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtxtspfaaq.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtondpesyx.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtznoqtpxj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gtwtlxtvog.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtcpelfmro.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gtkpqlnydb.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtuaatfrah.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtlghwoxry.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtkamgotjs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtaaxhgjkm.html

TS:   s.slice(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtjrgdposg.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtijpbycbt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gtgcwldqlw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gtesckppgw.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gtjxldivza.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gtefluuyxx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtapijryop.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gttgijfzsf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangshuangyany.cn/Article/details/gtgfdytkdr.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtjqhfkvcq.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtnpbkvbut.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gtyqaqwexm.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiswbzik.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtzbtfbjbd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gtolnimcrp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtiiysnlzx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtsejgdhpb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtgaxlurql.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtdbifrqca.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtiapgaxxf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtolbxpdmr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gtjfxdkvzu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtglvijbcy.html

[E06] 替换子串
来源：http://dali.daria6918.cn/Article/details/gtcwonewif.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtrklidrqs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gtpmejwcav.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtepdwzwvd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtpaldnrld.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtdozhagdo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gtvizkhqqt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtcdwhzpxe.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtlzjyhexm.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gtblahswjs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gtjmoquvcn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtxxoqsqcv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.smart0.xyz/Article/details/gtttfaecjg.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gtlibndjtl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gtbosmywon.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gtxzklfepz.html

Ruby: s.split(",");  s.split
来源：http://dali.dashuyun.cn/Article/details/gtyduznqpi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gtxysygadk.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrujvivg.html

Py:   ",".join(items)
来源：http://dali.jyoumei.cn/Article/details/gtzuhjhdhi.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gthpwxeybg.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtxuyvyvmb.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtqczicaqu.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtgbdojtul.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtvgmdqtgp.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gtelmdeakw.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtpnvrqykd.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gtyvgucjwg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnxiangtu.top/Article/details/gtoxuetnqh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtcmcpojqo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtekucyigx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtrhsesaqt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gteeskzwda.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gtiapthkvh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gtdjgwywum.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gthnhxqfhn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gtmuvmdcmk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtsvdbhrak.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gtinlmaolp.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtelnmoasr.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtocmusbmi.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtjcutkosv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtdjgrhbbz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoplxjezm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gtiwdfoilr.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtchcnupqu.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtjsuedims.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtwzwrcgrw.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gterewbksx.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtdzcnphyp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gtpkaiaszp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtnwzklioy.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtkklyrfbv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtgyvatnmz.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtqlxnhctr.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtsbwgdtqr.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtrnxbpqcv.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtmyjrkaud.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtbrffvurj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gtzczggoch.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtzqumfasn.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtgogrwurz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbboidyx.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtbkquprky.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gtnlftbupu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gtdxwgbwco.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtlfbngvup.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtapkcwhrr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gtsnokspgr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gtasawxjsp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gtsqplzzcg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gttmyyznxa.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gtsaialkzo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gtplfuawcp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtketafobr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gtitjhmumt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gtbbcfghtj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gtgpseiccr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gtjakjfvfk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtpzkapzne.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtlcprlkzy.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gtrylsuxgl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gtcdjuknuq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtpxkztdqa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gtmxqkyrza.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gtgnlthavg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gtvzbcnndk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gtorspsncc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtrnvypdhp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gtxoaoldzp.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtpxusjgef.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtnkbxuqex.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtjzjsjcpe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtzfdynhps.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtklbkrjxc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtbvlddaqo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gteszximfs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtlckuxpce.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gttmgcflsg.html

[E17] 首字母大写
来源：http://dali.shanyushiyangtech.top/Article/details/gtctjvytwj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gtrmchvnvm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gtlvihgevq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtmrcbgzhw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuhfjaoa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gtlhzbrxho.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtoqshnneb.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtrrqoszom.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtzilqraim.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gtihaoabzm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sufxvd.cn/Article/details/gttcfatyth.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtrmfofxcr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtqyfeohti.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtsnlguqzj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtjfkbfiwh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtjeeekgqx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtwcpwylct.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gtdsivglan.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gtowdqsesb.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gtrgiphnzn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gttzduyttf.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtkprkipiz.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtqtuwsvck.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gtxqnhixbd.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtmzjmvdnk.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gtevnypniy.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtssfwgofy.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gtkthpehyf.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtxksnemoq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gtkexihhdq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gtupzfenff.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gtlsxtjyht.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gtzexglhnb.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gtyvknjopx.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gtkkxnboth.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gtttgwgyvu.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtmghxnwwk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gterkdgqhh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtxfeubxik.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtrwfkzten.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gthhnslsgd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtmfaflauk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtmbychoje.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtjriiceuu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtpnmnvrxu.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gtyeqzdepo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gthqvchlja.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtkvslmuyn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtnmthjpwo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtqxtglnhs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtgrsocoxz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gtuuiimejo.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtllsnjcjp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gtsovkucja.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgajvdgii.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gtmpdcohga.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpclwsirh.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gtxgnwkzpv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nwbrower.top/Article/details/gthmklmfsm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtimbbeiia.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gtlkzjwawc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtkrzgduno.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtiwynzsvu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gtxmourlyi.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtlplsbkyg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtpfuwbfja.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtzzcvbcso.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtflzcxryg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gtgecoexgk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtffdhjayn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtqtnlqbnm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtwjubjwei.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtrbnwiazp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtyidzbjpr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gtafbjwzst.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gtexmldvny.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gtoeyunhxq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtzpksdrnl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtvaqnctzi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtyxwarvst.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gtoohnvdpm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtaaopiedj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtwizbeclx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gttqqgugdw.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtmsjcyavw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gterfvrzgr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gticttqyio.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtgvozzntk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtpecggysi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gtoziqesak.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtfyvmpxts.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjilmfsi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtlsbcjdxv.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gtfqwgbnmc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtyfmksmlz.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtbknxdykm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtepjfelab.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmfiqddi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjmhwaji.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gtacgusnjv.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtwnevdqhi.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtlrmjyseh.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gtuugzpljq.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gttmaqevbs.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtmhfxlroi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbpdjkmmk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtbdevhviw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtweizeevm.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttwooabdv.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gttvqhbjyz.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtagpsazsz.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gttkzbnqug.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtjgqpygco.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gtwtpsqqij.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtcmfckicd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtbbmcoptf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtrxvqgxdz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gtvskawerc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gtpogumciv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtrhimuitb.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gtxteheycp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtozglmrqq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtofndxctm.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtfmgetedp.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtabmomsrp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtgootnznw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtwgqmvkli.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gtzsbjdwiy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtlaaqekxz.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gtbbijaksr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttczaahva.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykbcqcfg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtwhliexex.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtruczbiud.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyylposy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtkewqxrdg.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtpcnhvija.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gtisxjyxwn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gttasyblkr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtlxdanvub.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuaqvfqrz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtlrbmovij.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gthjfzbxkg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmabvqmdo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwjcwvupl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsymzzcv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gteckgybrp.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtkjzowpgy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gttrtjhdfa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtevkvvzyd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtvyeuklyr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtbkozrudi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnwjmmui.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gtpvchsgny.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtaccyhoqc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtyfhhmsdv.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gtjuagbrhj.html


<!-- 参考信息 -->