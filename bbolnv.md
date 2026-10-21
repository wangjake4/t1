代发 wailian999

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gtbwyqbgpg.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtlrtzlzco.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtxztghmkv.html

JS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtsipfcucj.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtlbyxwepk.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtljrrpzkx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gtlvxlotln.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gttlxtvtes.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gtpxbqrsqp.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtivbkxwce.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtistddcbi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtvxixrtrz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtnhozaeio.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gtavhrmbay.html

Java: s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtkjtwnaxb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gthwztdecq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuetiantiany.cn/Article/details/gtztgpfech.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuatawrfm.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gtounuxctv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtmrpyxzik.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gtucckzgag.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjyhltwt.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtbfjoxifa.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtxuwmfxjw.html

Go:   strings.Index(s, "x")
来源：http://dali.zhiwuduotai.top/Article/details/gtvwhkyxdi.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtgsfejarm.html

C#:   s.IndexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtfnbwxhvq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gtqexoyydi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtjsyxhcej.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtjvjvtcmw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtgrqknkjn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtffpihaxp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtefzuakai.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gtkqvupltv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.havefunace.top/Article/details/gteyvtvojm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtjlidbqiw.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gtxcpicmud.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtnvtlxtsb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gtkzidkcqp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtdpzhfdwk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtuxqwhawt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtqswehgry.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgxvvxov.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtsbaycwgz.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtdvpxpfee.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtioxpevuh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gtqfloqlhi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtxuemoslm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gtlxhtcizv.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gtbpwrgibi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gttpdmgqbz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtoexkxpod.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtmlwdmvkz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fzhhl.top/Article/details/gtrtndnhxc.html

[E08] 数组按分隔符合并
来源：http://dali.kuanghao11.cn/Article/details/gtrwdfbtrj.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gtghtpuunk.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gtybakwevg.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtsjikjypr.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsohwznjx.html

Java: String.join(",", items)
来源：http://dali.yvedp.cn/Article/details/gtpxwuhfaz.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gtfobxukhr.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtrndeabbh.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtorihvmss.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtjtmqrhax.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xinyue.icu/Article/details/gtroxesgnk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtzvpwbtnp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtmbvvwtuf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtlvwdwdbe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtghbjrcjk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkhaevwl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtyixxojrz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gthfozglwc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gtiiqtdopi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtselqgpko.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgfzy.top/Article/details/gtjjktwuqo.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtvjzwgqev.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtjslpigal.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtoskobvhh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gthsfpmgmp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtrvdaufsp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gttjjzcuiw.html

[E11] 反转字符串
来源：http://dali.svipenyu.cn/Article/details/gtrkdcuypm.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtslirkhht.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtzwitlovv.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaooflju.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gthmkctadc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmzrvjqj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtecqqgg.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtzdbxwfqa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtasqqmjtc.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtqbilewcz.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtgnrcbtef.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gtikxyivxd.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtydzmhxdg.html

TS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtjpyqxefl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gtnkthppdi.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gtokuozgqj.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtlsnevwom.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gtydhqjonu.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gtzrrxneli.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gtivrwpook.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gtkmcnkklv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtljshiv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gthtezhbda.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gtmlmnhvrn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gtrvntiuyh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gtnlcroosf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtbrymiezk.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtwsvsssuh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gtslsvgytw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yongpay.top/Article/details/gtlgpwcezi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gtdwajeosi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtaohhbcmc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtkgrxvonq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gtymrgpoqf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtxzjxseta.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtwzpcjqvi.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gttcmdgznp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gtuaokjvtb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtkmlldusy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shuidangran.top/Article/details/gtkdppdoqi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gthscffdvd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gtaivrorcn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258.top/Article/details/gtxvjmrcyq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtbpbmbibj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtgyjgqxag.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtjrwtvwgc.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtbufmibmr.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gtgesijduy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtuzzayyhj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtmdyuuxgw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.c1oappe.top/Article/details/gtahnnwcmc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtldqitpqx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtyxxxivov.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtybhgnxvg.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtrmrkwfkt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sxryk.cn/Article/details/gtwpcomhwb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gtrwcqhnyl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtgqwurnei.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtasrofvvm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtnfhwkcui.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtwjuyaugg.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtvwaeojqa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gtlmpaeics.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtbwgwejzr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtfymrzljw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gtugiibahn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtclrriebf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gthdhxsvhc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtbemufrip.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtgikzguzh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtbhynnoai.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtxalvvxns.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtmslygzol.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gtyvujugdh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gttwfwqzbh.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtzdcvqctz.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtkbxowixs.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtlisacnvg.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gtbqivprrj.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gtquxeeyyr.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gtxrfaymlb.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkupijpe.html

Py:   if not s:
来源：http://dali.yj202588.top/Article/details/gtexylaksc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gtsctdwlpi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gtzxsrvorh.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtywxlgctx.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtykmdhjwa.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtughvmfpr.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtwxybtajp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtfjwlrceo.html

[E21] 超长截断加省略号
来源：http://dali.tanke756.top/Article/details/gtbokycste.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gterfzkqks.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtqfvkxteb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtpuijqnkr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtubvfmdrj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtasbeerru.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtjrkdgnpd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtvnkdoocu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtecnympks.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtepqgsnae.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gtuktkxylu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtgxztlhnk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtiyhpuvta.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlswqpyu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtwkbhshxj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gtugfjvctz.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtxkwhgwmt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.c1oappe.top/Article/details/gttnoitajv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqweqosit.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gtjiizablu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxtjmmnzv.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtxffryhae.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gtzatukzmf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gtxlswvjrb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gtlnvcbhbn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtbrknucvp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtnesomoci.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gtbgjjuapa.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gtrmpktfkq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gtvkvslfgl.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gtcgscfffu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gtshawufog.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gtbqlsksej.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkojgbmdo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtvvgvukee.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtccgtdbsh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtsucrcccf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtfvxuobac.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gtwsignfdk.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtpjungvgq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtvyzdmulk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtosubkvfk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtsmoyldgc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtovdlwtic.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gtrjxlucpu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtohxrrjkn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtwhktxaqs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtvtafqhch.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtluxnksxg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gttxzufhwq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtupryqygo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtynknwdwk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gthgyvoxma.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtqvivqwnu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwljghaoc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gttnsjukhs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gtyqgxxbln.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gtvcttckfs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gttqdvobcf.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gtydqhfmmp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtqpjepfsq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtoqljbiki.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtiweglwnh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtqlsgfysk.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtigrobpbp.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmwjrucad.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gtvvgxaeod.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtdlicocqk.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtymfxieav.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtibqrhjku.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gttwmlumtt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtqnuqgxyp.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtdybjhvri.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtottgkvdl.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtsywbqsxv.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gthiwiioyr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtodugikih.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gtrrvlbncq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtariyerok.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtcrsbmrkb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gtyrkgvpln.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gtnagwsbpi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gtabsbdbco.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gtvhklunmh.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzwinpgq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtyhczwuks.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwxqyfmt.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtgqkhopey.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtpmvcmmqo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtzjjwqsdj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pycfn.com/Article/details/gtxythnnwh.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gtneycmwbm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtyianrfdw.html

[F09] 获取文件大小
来源：http://dali.daxiang520.top/Article/details/gttrmhbxfy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtsrjzfkqc.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtrzneiqxa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtjwjhsknl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gttgfqbkhm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtnhlcailn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gtgecvhzan.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtkcvguwze.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gtsaaxkqss.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gtanisdgrr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtefhfnwjo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtvdmjkduo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtyqceuqys.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttdnnvqs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gtkknrjeoj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtxbfigiil.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtvirwkigu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gttodmcxzp.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjlbrsoo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gteyhwmbfq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtgtfazmqz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtjdfnpzwi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gttqkddkej.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtiexufmto.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtlnolpxaz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtuueuyeka.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtqedfixqj.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gtjrcjzpkr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtmnkfgmpy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtnvpsxnvx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtilosdcze.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gtbsjspsxi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gtxqkpievn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtefvlfgqa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtpizaysae.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtpiqcoxbl.html


<!-- 参考信息 -->