代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gtbzegtjoe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcdwnxqd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvugqhgv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtokclpyrx.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gtwqgfikid.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtkhhksose.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gtafarfmdd.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtdiqjnkcy.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtlvzcaxdm.html

Java: "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtuzifqcfd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtlbemfklp.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtruwapqwy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxeyjjpl.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtpcnvrxhw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gtdgiyflfr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtnxleqlyj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtqpxvqynw.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtkmvjtxhp.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxthzgqf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gtmtfpyued.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gtvzjwrhvx.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gtjtutnsrm.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtawsstcvz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtkkutdfyb.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gtjlvpbvdg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xinyue.icu/Article/details/gtfyktygsi.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gthbenhaen.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtpxekuand.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxewtbcf.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gtnupdcigo.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtpzexkvmg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gtwmlcnogi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtppwnwfjw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gtqgienkwl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtfnmffdvx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gtviiaqruj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtiixunwer.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtogimxbmf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtncblfngk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtipemltda.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtofkvzexr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtxyulwsxq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gtpwuitsyi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtqjjwcgih.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtngmdvabq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gthhlctawl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtuhnynqgx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtmdsxiysc.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtqzvzawam.html

[E07] 按分隔符拆分
来源：http://dali.jianghu66.top/Article/details/gtnenwtady.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gtpphrcfff.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtmvcbpdhl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtyohwemve.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gthwmyrpyk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gthervredl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtpjdtnhzj.html

Ruby: s.split(",");  s.split
来源：http://dali.jiagoushi.top/Article/details/gtxoymvzrx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gtcrmvmziz.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtueguhpsp.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gtspqmsoli.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gtkndtozzc.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtmnbgjfkz.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtoskcapcp.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gttllunhgr.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtqgwcmcdu.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtgvufrxdl.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtmcfbople.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gtinscrjin.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gtjuyilbyf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gtlizueued.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtahvhezzc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtzjlbhxye.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtclziuemx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gtuymtwxki.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gtoatmfxxg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtwooredji.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtpsoffsqt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gtxibwqixi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtxvrjftcj.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtlqkcadwv.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtyoxvwhnj.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtrhqmtinx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtdofjfdhj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gteiehvfdr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gtatnxzwep.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtwwqtjrrx.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtsnehriqy.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtwmqftnqp.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtajcyygvw.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtvxqvmpxc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gtwxcblyus.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtentzynfz.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtimpokxov.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtxiliqiok.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gtnandrthq.html

Py:   s.count("a")
来源：http://dali.zycfv.cn/Article/details/gtjbyppuou.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gtwvosqmkp.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtgcbobxil.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtcemztupp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gtnbssvynw.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtulstyxoo.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gthlqumjac.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gtdifcsmut.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gtvedpytge.html

Py:   for ch in s: print(ch)
来源：http://dali.fzhhl.top/Article/details/gtxtubdlna.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtsrhvuepi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtsggaxtbf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtgbaifdib.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gthuupsyer.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtqzvulvew.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gtbcuijokr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gtzxqxpnuc.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtvrpmmpjj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtilbwhmez.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gtwrfngdlg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtfzpzzolu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtmaxlmfvn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gtuleaxxzh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yanxiufei.cn/Article/details/gtjjocikta.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtzuyhipsn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gttfjhsyjc.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtrduzyczq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtkqzoorol.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtbgehbxof.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtmlnjgmng.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtjwwzwlks.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtyhrnsaqm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtedcyitmm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtcjnbxaby.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gtaijaohzf.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gtkakevgle.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gtcvmocwwa.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gtvfjjmriy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtspqhhteu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gteeiidiib.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtejrufmys.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqruqcwpy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gtpclszbqn.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gtivuanarl.html

[E17] 首字母大写
来源：http://dali.jlsjyb.cn/Article/details/gtgfwhfpfn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gthctpppid.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtlifunkks.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtpfabuemu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gtpluixrbd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtynastpyi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gteoerkflz.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gtabvmvwsg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gtawbstboh.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gtzzukwocg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gteugfecdq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtnyzvtptq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtvmpexwgd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtpqsbexbc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtygabqihw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gttwpehtdb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gtpzhfixho.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtwgeaiuzn.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtploqpgfd.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtmryhwsfs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gtrlkpbsht.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtaujbgqfs.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtiwkenrym.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtutlhshuy.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtlbxmbujs.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtzfdwppxv.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gtysmljgki.html

[E20] 判断字符串是否为空
来源：http://dali.zhiwuduotai.top/Article/details/gtexhcelmq.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gtbteyecus.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gtyydieuxs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gtqjcvdslv.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtorxwyrgo.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtsithxsyu.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gtqckyzewt.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gtqgmrwydg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gtsxyqjapr.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtbwikwjgw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtsxrmyhex.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtuhcebbcf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtgdausgpz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtwowqydpt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtitemxurr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtgbatnqcz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtfbrsbiqg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtohvoajfu.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtwqogjcii.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gttrjaaimr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtjlipuasd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtermjkror.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtkfgchnci.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtrcdspiyb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtqhvcseqd.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gtrjcyxkzg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtyowjyace.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqyxerzcl.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gtlgylzzca.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtkjlrbxbn.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gtdyihcsnl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtzjvrgfxs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtuzupeldh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtuzkdoypn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtcpmnvhaf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtsjkybbge.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gthivttxtj.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtcwgotjtk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmauhvjkv.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gtuzorgwbv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtoohxeqjp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gtxhogjyae.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtabvvznnw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtzhndtxac.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtqvoviakx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtrbmcdblo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtrmnohfhg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gtwovnxfyr.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtmvgftdhq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sweek.top/Article/details/gtiskpduwm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtggbffxlt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtttulgrtn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtloaoqeyd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gtrjlphhfr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gtaotnlwgo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtshfqzxux.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtdychmtrm.html

[F04] 追加写入文件
来源：http://dali.yanxiufei.cn/Article/details/gteurfnmpw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gtrzeaiumy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtrylwtwco.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtarnapthr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtnvdezjmm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtbyrbbczt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtitjwrviz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.bjfxy.top/Article/details/gtszcxdxrf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtbtbyzgzg.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gtehemmdlf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtclaivhkw.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtftjsyxbb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtmarexnsm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtzwbwgdbz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtceghfaqi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gteaoqxurz.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjiyspsfq.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwyizrkkf.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gttoolqxvi.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtopvfigvi.html

PHP:  unlink("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtspsalpxf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtfgchlwwt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtvjprmvde.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtvozjnpyq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzsdbmhsf.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtrylngnif.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtqjqrhxxr.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtnyubrwiv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtlmmoofmr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gtizcmmsoa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtoxwqdupb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtizxtxala.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gtdwkvjobl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtfbhkbtvv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtzeivfhvy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtkzkquxam.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtdsnqflfl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gtmrvgybro.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtdyjhyiaq.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtzrsdqbsj.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gteizjhjjz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gttdqagdka.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtdekpmygi.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtxwzzxbvu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gturgzbicr.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtfsshiwti.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbzndxig.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtovssslti.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtuvqpbblu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtoivgckbm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtaivibcnm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gteyfpriki.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtldguracd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtvpvsogyw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gtrxtnpjgb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtabgeufoq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtmmpdcthq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtauvqzscp.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtothvdgez.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gtrxmmcgfn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtpppowsmo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtngzonhwf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkmimplld.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtmscmhgcl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbrildabg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gthopvhxwy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfjywsulz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtuhtmkklo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtgdzjgvwu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gtjqzctizr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtynvsbesw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtrsndkmlr.html

[F12] CSV 读写
来源：http://dali.hongshengwenyu.top/Article/details/gtbmqjxohh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gtlhsvqkxj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtwdzlshns.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtgetrhixe.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmspfanfq.html


<!-- 参考信息 -->