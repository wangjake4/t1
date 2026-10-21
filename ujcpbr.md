代发 wailian999

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtixlpttyc.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gthaseenke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtgxgvektt.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtveuiztab.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gtggdeihaa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gtkytrinbx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gtrcyyknzm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtomdstccp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gtkmjaxzat.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtzuiojhee.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gtujaavgpr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtbxucirrt.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gtikaaollr.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gttbkaaahn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gtmuebahbj.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtfgtlrbxr.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtrstlccbm.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjdrwbrj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtudsgqkrw.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gtbzuelpsg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gtdhbvonvh.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gtzhmgqgfd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gtwsedsdng.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtlymscoed.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtffgkoxkv.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtyduububl.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtfavzvffw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sweek.top/Article/details/gthzteezcb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gtkhlnsxqn.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gtxtuepzaa.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gtlzdznbzz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtmhlhbnan.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gtvrtpjulb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtzpfrbyfx.html

TS:   s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaftuxobt.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtpugbagnn.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gtnaxyilbh.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gthdjlhvfm.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtdxrgzzbt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gthaqztmvw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gttemljhnn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgufenzy.top/Article/details/gtpmpvolnf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtgmhsklnw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gtvhwphnvm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gthdwdfkqx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gtmazakquc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gtiuxoxxrp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtswuhbkfu.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gteowznijh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtcydhzbwf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtdouditsh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtzsplaqbt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gthoubczmg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtxsqlbhkd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gtthtnbxos.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtwafscnkb.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtsimqreay.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gtkwlimgds.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gtxwcfglgi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gthvyyscaf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gtayrfwbjp.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtckfbbjca.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gthdqgkrap.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shuidangran.top/Article/details/gtljpddkns.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gtcsurcssc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkfjntej.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtxfukgthz.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtvzfgoyub.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gtyowaeacx.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtzlxtcbyx.html

TS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtmotyrpej.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtauzwqtxs.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gtjypujpqb.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gthgyuxxtj.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtnmejylse.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtuafpljry.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yangfankeji.com/Article/details/gtjwuitwgt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjpnbwkc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfekebbxp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxofnzwi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtwijlycyr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtcakpcynv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gtquuywrwx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtrzaeqqlt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gthtbxzayy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtdzhbgkyw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gtowxkltqz.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtxgjbfbue.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtbrixiaeo.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtqovshyoj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtmvktsrti.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtbovbkvvp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtjdbgxcmu.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gtxeaynxrj.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtbvxujqxf.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gttdlzzaqb.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtgpzwoeke.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtyrdzlhel.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gtlpnzazsv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmrafham.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtpxmzhddl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtvuetcpcc.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtrygsbyyc.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkalsjab.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gtnnitxbeg.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtlmcuborx.html

TS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtjxflfcao.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtfxvbjlbe.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtpfpypxux.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gtgiuwsahm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gtzyoldhlk.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtadgmrwvg.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtdjbdtzpy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.birdmap.top/Article/details/gtzsxpjknt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtiywlvwsh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtzqniwnpm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtopdgunvm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gttkuusghn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gtjefwvcok.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtanazssug.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyeltbpo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtthmkxmpc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gtxmanfwki.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gtufihhrsn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvmfdyrmt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtnhrxnsgt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtgnvqwllu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtgnfofnlq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtcmvyoqxh.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtqorrwkkt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtbbjyhlfm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gtexeeused.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gtrmquqvht.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jlsjyb.cn/Article/details/gtdjcoytqp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtzxabtlrl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gtipxbahzp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gttzmefvch.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gtmnhdapgo.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gtimjbmfhz.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gtkpwzvgfw.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtdtminwig.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtxcgkewjx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtzgfpjzuq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtwhrmpjjb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtrmaxrkso.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gtedrddttu.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtmbevguoe.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gtbmjzxcvq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gtbxcxbsgb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtahsvtozf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtgbcpdght.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtggbyxxdz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtfzvebdfb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtygifmfbt.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtlzvejahm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtggpmedej.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtibhqnxnx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtfrowjuyg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtuczgugdt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtakdtdkaw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtmbkvzrdu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzcsuaba.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtqxryoxwm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gtkjdkyuut.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenjidiqi.icu/Article/details/gttnkxoloj.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gthokjfmbg.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtlstpktbb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbxlmhgl.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtwzeusugt.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtneqnmdrm.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gtfnyhwxif.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtjomeqokx.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gtpwcpfcuu.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gtjwpcatkx.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gtazlbjynw.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gtotggfswo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gtmaihglzl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gtrermqmek.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gtfsaxmeyc.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtetisipvc.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtkeclznya.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gtfoojhscl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gttqzdiunc.html

[E21] 超长截断加省略号
来源：http://dali.cqqwz.cn/Article/details/gtzdmlffzj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gtsebsnoud.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtaivumajb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfcsmhib.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtstydzfbp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gthoeklvki.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gtyewmujtx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gttskramrs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtmopxftan.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gttvvyzfln.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gtjdrnloxq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gthvkdgdga.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuxoiwhb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtyyqnbxtc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gtvgjewscd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gtlxskuolv.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtcyhsxkvf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtynyipphr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrzctrqtp.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtqnqygfnw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcqxwvfww.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtcjhwqdcb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gtljiciwht.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtnjtsfemk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gticeyrqgo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtvxoxrior.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtfawnzntf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtewdnpxdc.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtkpsangxi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtdgaedorh.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gtcvysoufc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gteztzoeig.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuhmczvxd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtozkevhmw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gthqgrdadz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtwronfdpi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gtgfeieprz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gtkpbooibp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gtjnopdgog.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gtixlybehb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gtxqzrtlwk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtfrlczxzj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gttkjhocfj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtmbagsrzr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gtalgtshnn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssoprtqg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtsbablonq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtwfagbdbm.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gtgpxphxct.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtyoqzyfaj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gtwqfvevth.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gthmwtqtnh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtsnkzxutu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtfwtkfkuu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbrcxliv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gthybijpvs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gthkrlqymu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gtwhsmcslf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtqtbcxmfe.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gthjaxsonc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvjajrsut.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtbpupxuxp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtwjunxcyy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gtokvudjho.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gthrakozjw.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtvlophdni.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gtswqfrenf.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtknlowzyf.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtcrsbtzlx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkikaeazv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtntbzdngq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtrodskret.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvdbofcrt.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gtwtmtxxyr.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtrifvhojw.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gtbcyushrs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtxetowsqx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gtanxfwmzv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtupgdglvu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtxfhjtluy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gtzafrrbfe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtozwcspcn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtlbfeehxk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvgjfmzk.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtfdijxciu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtewccooxd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtbxxxvble.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtlneebfyk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtoqtsddkw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtuzoyipar.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtqerlcqwi.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtcjhdftsq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtfbuzkrws.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gtggiktwlz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtsvsetymr.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gthhjatkdo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gttbmpbdma.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtahcwvbcc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtejhtdzrd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtkjcopish.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtegefzatf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtemfwfmvf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gtdnnsrcbi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdoposbvm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtkwpprivi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtegzvaikn.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtjdzhylno.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtiptrvmcf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtiyxapvfk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlrnfhfrk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtjegnpgao.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzouorcs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtaftjpnzw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtwtakrluo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtjncmkpfi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtjyduqlop.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtfuuirqdz.html


<!-- 参考信息 -->