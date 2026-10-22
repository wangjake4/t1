代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gt2hsgiumpp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gt2tufocpjm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gt2eswbvmbx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2xzpbydto.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gt2kuzkwaos.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2ogaknnov.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gt2tqgkhslc.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gt2kwnwlbik.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2puulduhb.html

Java: "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2eityunpr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gt2bvaafqvb.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsvecsoh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gt2xaanrkrj.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggfzscct.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gt2mkjzdjai.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2weabpkfk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2dlankjnq.html

TS:   s.slice(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2ltythrri.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2qjymhzie.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2rabidnwg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmpmjmai.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gt2oedlftsm.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gt2xedgfoen.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gt2tcryhhmy.html

PHP:  strpos($s, "x");
来源：http://dali.xuanzx.com/Article/details/gt2rwiuxioo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gt2etqojbwf.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2ktbpaevn.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2cafojlst.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gt2ifltzqyt.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2bhvjwavv.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2thieigvp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gt2dvcwdowo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2iwpyqrnk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gt2vsliqyvh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2idwciapb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gt2kkocwysd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2onhjbzgo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gt2nzleohlp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cqqwz.cn/Article/details/gt2jaepchkh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2sgqqxchz.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gt2uzjsruqe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2rhrligxh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2oxlwtzht.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2ftsswfjj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhfrppzj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2jolaxkxz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2nipmersx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyhjrqay.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2ieimwpdm.html

[E07] 按分隔符拆分
来源：http://dali.zhengqikj.top/Article/details/gt2yyrvqxkn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cheryme.top/Article/details/gt2puxjacwl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2hnqfppql.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gt2jfvajlvj.html

TS:   s.split(",")
来源：http://dali.sysykeji.top/Article/details/gt2vftlcbww.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gt2upotnvim.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gt2tbgpedlb.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gt2vvvdqbaj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gt2pixeqopp.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijpjkjtw.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gt2yxzdnbih.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gt2bjqkzpci.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2wzbvzvme.html

TS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2xwctgctx.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gt2xktxnocq.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gt2ihfykfbg.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2bswkymrf.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2svgvwuwq.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gt2trmipkpv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gt2lklgvlda.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gt2opssvayx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gt2dtbwxksf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clomfswe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gt2hhnfavjr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gt2ufbwfbmt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gt2fuayytvv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gt2zfnehafs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gt2hprmivhk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2taqjavqe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aibaodan.cn/Article/details/gt2ljsltsgk.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2ybkhqqdm.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2bcxqcfxy.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2lrbseali.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gt2xmcqidmi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2gjvejrog.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gt2ngkdeccj.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2cumfsvhs.html

Py:   s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gt2zuypumth.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhoraqnc.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ziyfptah.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2dfwprtfd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stvdfebw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gt2itraojbc.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2mqcucghf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2ztbopfrv.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gt2dnlqhqlh.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gt2fglktufs.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gt2thydmbdt.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gt2ubbxfbbs.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gt2xlcflogv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gt2fgarnjwv.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gt2fasioyxk.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2ldidftrt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gt2azblnrcu.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2pcmrmcxu.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gt2iiycpbwe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gt2upmmevbl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2pwedgiwe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2cxoqfrwi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2goyjojij.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gt2ylkdqtcb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gt2ohtaiupc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2daaqqhav.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gt2ptoywvpq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gt2phxjrjmc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2rjmgzjba.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2horvbvfh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2anxbshkj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2tkyfecog.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gogol.net.cn/Article/details/gt2tteyvigg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gt2fsptrthl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2suxmmnuj.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gt2eibnukkv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2vhbkfpwf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gt2eziskvav.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gt2aukoaibi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgtjlzeh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2tzclohka.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2cbxtpnnj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gt2kxufzmbv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2paerpcdx.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gt2aqfojdfk.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gt2orbxbbiu.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gt2bwmphcle.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2woyanqfj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gt2ttcwxlnt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gt2kadoszqz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gt2qffichtc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2axccecih.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gt2samavdre.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gt2dzuohzxu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gt2ycntusot.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gt2ubvtxouy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2cnnvfzun.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffpheqwk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gt2omjjroxp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2erpmsaqn.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gt2viusftpf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gt2ukagsenn.html

[E18] 模板占位符替换
来源：http://dali.sufxvd.cn/Article/details/gt2ovdxfaqw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gt2yyurizvx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gt2wzxhnkvq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2najcuycj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2uccxsjsx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2xpwntxio.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2tdzuajcz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.c1oappe.top/Article/details/gt2oadvklpc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gt2urwvwifi.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2skzyrlqt.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvujgvty.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2tzpqcncx.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2hrydvlod.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gt2equmnnrs.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gt2pyystwuk.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gt2jhbctnfy.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gt2kzngkuho.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gt2gagminnn.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gt2dvisrjtj.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gt2ciuuqgtl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkuoqtid.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gt2qxqgxqlh.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gt2dewqowck.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2jigumdcf.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gt2mnhgyyxk.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gt2qqlklhlo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gt2adpkwbgo.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aldysrrj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2rklmbclu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2ldhewgip.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdrjohtc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2plyvpmhq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2nhqcuqfm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gt2qgthywbi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2teaysuoz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2uemavhjn.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gt2tngwgoue.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gt2bqtzmuqb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzmcqhgx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2atrpjmxk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2xasengqm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvnppywp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqctgwgy.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2hjgurtcq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2zinguknq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tucnbluc.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2bqhbumco.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qkayvzaq.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gt2wctoaeuc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gt2fwsbwemn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2atwtqbqe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gt2yyhtnbgp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2ptsozzmk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2nvhscwwd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtxueixb.html

Ruby: File.read("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2skpodhsk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2jzlrieej.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyhvmaqj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urwhooie.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gt2flftzqtm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gt2duvepdcv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2gkzxzdzc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2wmwuezoj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gt2wbkzrynb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gt2zjytijky.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpqufwys.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gt2faadkmyn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gt2ivneyykj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2mrvuahbx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2gdznemwc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2oyjkguac.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbjrstva.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gt2thbhzqfd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gt2uwzoizqe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2vayfotkn.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gt2njdsboxa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2kxrtvedf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gt2ydfwdilo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2dudepmag.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2crhriwcv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gt2vecaqvai.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2ylkoooer.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gt2vqwsjugv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gt2ymxeffth.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bfxnnkok.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nwbrower.top/Article/details/gt2gjcqnwgm.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2xhquggmp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2cgdonvuy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2gdhmeqni.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2cjbvjlll.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gt2vaqpxvsi.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2kpdcfgki.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lekxqwgg.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2ieukyoms.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2zamnsydw.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2wyployug.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbdcisia.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ofvhawho.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2xdzfgblr.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2yvbrsrwq.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjxmsdyx.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2fwmrvhyo.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gt2ngafkbeg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2ujypssat.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gt2hsinkxsk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2zcqqpdcw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2aizeibzz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gt2utfxspvs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqqljrlb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gt2bfglxpor.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlokmvnh.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2iiquyjok.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gt2qmjrwpuf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gt2survfbfr.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2zijxhejx.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2macvvhwm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2jyjwflfv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2vvbgsfvz.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gt2hyskpwgi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzijgswm.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gt2tpfvacuh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2mbidnetk.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2unifkqhd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2mbvuotwp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2yajbxjda.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2ocjbtnbs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gt2wlsktmga.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2awlvruxs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxwhxpfc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gt2onfkbftz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2shqcrbvw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gt2davmomip.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2ejxauldu.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2cfzgbnjw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gt2osguxtrf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2nzwqjvyr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2mxodnqvx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2jsfiwadz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cftztafi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2nqqiuxow.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gt2apeskkhb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2arhnudfr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2gloiarks.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gt2edobuvdx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gt2juguqyhd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zyzbhqlz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amihsetk.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gt2igrusyic.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gt2yapjvbbv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gt2jkptoctc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nwbrower.top/Article/details/gt2yrbnrbty.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gt2zpxvwvar.html


<!-- 参考信息 -->