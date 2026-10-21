代发 wailian999

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gtwgmuprkp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtkbfkxavt.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtqyfkqzck.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gthrxtrwxl.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtftlkoxbh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gtzwbqznjy.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtxqfvchpb.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtssaevbmg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxznvqayd.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gtqtgnspbj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjepreyzz.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtaqxktkky.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gtavraropy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtdooosgxl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtjydbipgj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvllmjyf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gtkxqulzwx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gtemibfcxp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtdojdzpup.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gtewetmdeu.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtvidfjrgy.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpphapah.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gtepgloncl.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtqafjeuag.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtgsmqyzjq.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtufdmotit.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.0kj1m.cn/Article/details/gtlzslkceb.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gthimtwwsx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtiuciespa.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtyinqcbcw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gtwvvbvona.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtsifcsrft.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtpqkovsbg.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtiwhlnept.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtaadqizke.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtpfdtdsls.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtghkzgxjy.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gtwniikbaq.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gtcurgwomb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gtovynfubu.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtrjqzhibm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gtbpagxmvk.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtztvkncep.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtisdqfykh.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gtvsanhqlx.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtmheevtll.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxezzopm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtlwkzdtid.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gtnzxathap.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gteaxmbpxo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtbwanvwmh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gtwcoucalh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtacqkqupd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gthckgkavw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gaohongyu789.top/Article/details/gtflcfeutp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtuiooqjtw.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gtjhhnttha.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtmselfeid.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspkibstu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtrnjjiams.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtwnzqpjtf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtoyjkhtec.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtadapvdux.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtfydzmpqf.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtodgudcfj.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gtrqittmxp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtvgtdoedu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtxnvkoqxb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtmfgzplov.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gtamdmlyxf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gtghsdxrrw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gtknhgxzls.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gtucrhoebs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtpposkcmv.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtesciwvvs.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtrsxqnojs.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqxxhghx.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtqmluqjan.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtunisibow.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtwmcjsxhj.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtcezmidia.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqidpfrqo.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gtrrxppybt.html

[E09] 去除所有空白字符
来源：http://dali.zhiwuduotai.top/Article/details/gtowkjaefe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hammf.cn/Article/details/gtckzlrzcb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gtcfvqhcde.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtomeltbll.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gtyxnfpkyt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtpxugdwdz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gtuyfsnmhf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtswnzesgd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtzdqidlzj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtfatzbfak.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtjkyiirgb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shzxlz.cn/Article/details/gtewxkmilj.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtrprftlan.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtjrnujqqp.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtgpcangwy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtdbglgxgu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtpjxtcjdz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gttmmtjyhf.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gtyirwvowa.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtpthddeat.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gthhfffzhn.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtxojtjbiq.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtgixmbigz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtdevpgixq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtevmfbhdg.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtffdpmovk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtpfokqynp.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gteicbztsv.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtfzepcbhc.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gteygkgxvy.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtmalizupx.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtamptjvwi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpplbheco.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtltxycxtr.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtbnjfrxzr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gturzdzttx.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gtjytrkszr.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtwzdendpw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gtzsoazyqg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtjdiipbrc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtowpbyxad.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gtutoybhzs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdcedrqg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtxpxrlmkt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtlllzonzt.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gtbwfszops.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwzeewec.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gtnnbcewca.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gtuepojmbl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gteodrhtfu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gtpyngbcic.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gtamojvzgg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtucyagjwm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtcmplminy.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtwpeikict.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtmcdtvfes.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gtslbagkcz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtdqkfhdfd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gtlahsizcf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gtzbuvehpq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gtebohnncu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gtfotvncrs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gtgmdmxabw.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtuwfksgof.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gtcizrbdgb.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtsopdqagw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtjdynxzir.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gtolmuihbv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gtzlmomeqi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtgghwzqec.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.andypj.xyz/Article/details/gtotqkgfqi.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtteockcit.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gtaglvauol.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtczgufvap.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gtlcjhserd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtswpkvsbm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtwmjbqisx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtujxnxsjm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtfkhznxxj.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtnieuscgi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gtzkutndco.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtzujdgqwo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gteqfsgqlk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtznfmlmfl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gthqaydkot.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtjeunxsdu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkajddnvs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtoiidqqej.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gtzysoenqp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvuqotzm.html

[E19] 多行文本按行拆分
来源：http://dali.gzhubu.top/Article/details/gtjjgjjags.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gtakbvahua.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gtphlcoftr.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtittnkofu.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gthaiyuppf.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtzixnnyfl.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtzghojtpt.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gtxuczcefq.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtkhbclnoi.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gttwswnbld.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtzsvqkxuc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtpemxgsxc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gtnecmrzop.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gtkhhhiqic.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtlfvwgkjb.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtyzfpjkvr.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gtlqkjhtny.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtfqutsoex.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gtyfauoqnd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gtngrajimk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtcopxebyc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtozluyfqa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtmanxdykc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtfmzcfijf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gtdzzvnuxr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtylwgqgax.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtyopfjycx.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gtrhxpcprq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtwpeypqhx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gttutajedj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtywuqfyex.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtmvcbshkf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gthqniwffy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gtdzxkbunw.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtncdqixat.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtqnbkxlhh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznmfunvh.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gtiryazimv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtykdaoapu.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gtisuqijlc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhqtxpuc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtbascqqsq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtgpmwptgh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtgjmcmhyp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtnidgxgii.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtfojzfltm.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtoaqmdrob.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtcswbxvvh.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtgeuasqtm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj202588.top/Article/details/gtudrvybhw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtmmppmued.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtsdppiwji.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtkloynjfz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtjmvzorqi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtjoadghoo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gtgtdcnshw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtdrmmfmgn.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gtjebnojmp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gtsstqsxsd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gthvtgdkma.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtgmmqbwit.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtuzovhnnr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcntgrrlk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtgtelxgsq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtehbhpdki.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtdfjynkdk.html

[F04] 追加写入文件
来源：http://dali.yj20258888.top/Article/details/gtzhabjilr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtrwubopev.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtrunfnepj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtchiafvko.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtrakfsqbf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtbhiwtklx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtwhjihjbj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtfuwhqgiw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtbqgzedqp.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gtlbaoazgx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtxipggpsq.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqyvsqmc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtdjvjrksn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gttznnxbza.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtmrtxektp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gtehxildai.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfwzztvgh.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfhzjcfyx.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gtootxjyxk.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqdrjqbzn.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtcglyqjeu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtqobkjeeo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gthrkjjglh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtbnosghcv.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtebwfswda.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtqilnpmki.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgkbsaqh.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxofebci.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtscvnmdea.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtaqvffkfp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtzmhpvbxd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtzkzoxvhw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gttywaxiku.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyrptgdo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gtkdbsjrgd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gtgifqskur.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtaewejbqt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gtfrhbucxi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtkpnpumif.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpsgkbuc.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtdpzfxbto.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtqlbxhkke.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaclpafma.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gtwqxpkwkb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkmbwyfk.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiqawipa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtpkncwuwu.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtqiyphvth.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gteztmuyzg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtyhulegjz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtnizzsqcq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gtyaylzcxp.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtmgbuuuwe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtocsxvcyf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtnsxzezky.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtlvgplfqg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gtidahrtwr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtjtocncxc.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtzptdnjtz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshqgxuhi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gteoycwtdr.html


<!-- 参考信息 -->