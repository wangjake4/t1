代发 wailian999

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gtfiyzdjfj.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtxqcrauug.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gtfhgjnncm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtmydgjaoc.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtzqmqwynh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtqhzfqfar.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtzhfnpcmw.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtorgysphw.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtamoiiywj.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtczlduidf.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtctzfgvms.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gtchunzlwg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gtqhfxbiwd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtzehnwouu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtunuuuebd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gttfywhfch.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtdrraxdcg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtmzvlxadh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gtpnbnyovb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtnxexbdyw.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gtpshaxqxv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtdlbhqpki.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gthoxpykjh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtwdiakiet.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtvvnlcktk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtnzylecff.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gturvuyhhy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtseihhdto.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gtwgagldpg.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gtdxnenawb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gtxrgjntoc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtktxjbsvm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtwdwwrqvx.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gtxcqdghot.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gtyqlprodu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gtdljocuqt.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftxgymgw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gtcugfaeej.html

[E08] 数组按分隔符合并
来源：http://dali.zhoulong.xyz/Article/details/gtrgmpznsa.html

Py:   ",".join(items)
来源：http://dali.c1oappe.top/Article/details/gtivsvwqjd.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtoumeuykj.html

JS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtfgxcaano.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtxbxadezb.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtpilhpwco.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gttxscdxcq.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtrtuhfrdi.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtcynqvnmt.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gtzqcnhgci.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gtekxeuzqc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhixingplan.top/Article/details/gtabuultwc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtzffwaayf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtzdbjmutl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gthmxpsukc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gtlbsfggfu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gtsbbjmmfd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tian-w.cn/Article/details/gthvuswzhy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtrnmtevlu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtgrsytumv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gtpsjrkmti.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtnlourrnj.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtbsarabsk.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtpkccjqoz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtzubzuwot.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gttnfivevl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gtbjrnielg.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtarbtjdxn.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtbizezwqb.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxennadow.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtthiubihe.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtqkkobwer.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtgmljglqn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtvwrcvzpx.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtsweyqjdh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtohhunftg.html

[E12] 统计某字符出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmwqzwyk.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtwsyaggix.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtljtbqqjm.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtjzeanndg.html

TS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtajwdohpr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gtyoreevtp.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gtoftnxgku.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllcrcvka.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtwotswreg.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtiescftov.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gtpvkvmdqw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtygffgshx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gthmxnpikz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gteleotcsy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtlwzfjlar.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtvaoedmfw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtwobdbztf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gtvjxcyxmw.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtljnaqmeh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gtpooiwbuu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtdoccicjf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtwbtbgxkg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gtbwkfcjfr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtlbdxicfq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gtwcvuquye.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gtqpjwxzak.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gteimeixug.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gtyrujveto.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtsfodxaeh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtqasrljlk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gtuoagqkba.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtlwemswjy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gtjcdyyxcq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswyevdgn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gtnkltbvmy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtznaflxdm.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtoaimjzfa.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtznmehcoe.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gtmggyivjl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtjlhnvqnw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtnmfplyyn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtcrebkpos.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gttyxwszbr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gtykwrmsni.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gtayhrpttu.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gtzqvifuqn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gtnvicqvly.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgupclfl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtsylgyiwy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtzmkxphso.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtemnbfvzz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxhjjjka.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gtpnasdhku.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gtwcjrnzwg.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gtwatfthny.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtrfiiyzad.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtfjziekdr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtdafjzsvn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdndncqnc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvdgphhb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtrwjzypvg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtqaedtlwr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtrotsajmz.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigufen.top/Article/details/gtmthskudc.html

Py:   s.splitlines()
来源：http://dali.yj20258.top/Article/details/gtgexikmsl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtkexyjgmu.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gthneprrdd.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtvojynbau.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gtchuxpekk.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gtknopiyxl.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtzhydvgua.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtopaoshhb.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtqcmonrwt.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gtrrfwckge.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gtqhywhetr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gtrxfdxjgc.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gtsizzdnvd.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtrxwipohx.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gtcupzcdgu.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyisgxlz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gtodqbhgdx.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtvvrisaad.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gtybxnzyte.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtiqewjdel.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtobxfufxs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtottrpokc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtdtylwfng.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtrsofrklm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtblyncnfd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtqkkojvci.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gtxpcvezyz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtzjqsridw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtjbpbzddl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtqaxpteho.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtfdplcsad.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtjbekrtmw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtnlzxindl.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtleacgbrm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtaqqcqtok.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfwewqzn.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gtisnacijs.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtwfyseodo.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gtgpcejnal.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtsdgmrepk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtuigicvyp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gtokllvvmb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtrxgmslje.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtmadjgthy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdibcvqra.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtxtwiqyvf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtkiiziszq.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gthkdsiuhi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gtbjnsruuf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtdgcjigux.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtxzyvrvxv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbygdkttv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtzbkrpatq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gttytyqgrt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtddxmavnb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gteugmzgus.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtfjgbwlng.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtyqygbvzm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtjpzcmjmz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtddftuyys.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtnvdexpde.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gteglztcji.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gtfvlvfpeo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuanrqksq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtfvmewvdm.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gtgpoxawnt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daria6918.cn/Article/details/gtaiabgkso.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gticolbnqe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyhkkkru.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtacfsjdxl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtxenifnud.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtvaiqkcxe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtvbjrxdxu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtvjquptbh.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gthmwxfpsj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtieklmmxv.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gtxtpocwgu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtuqzlsbgn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtcskbgeji.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtferijdju.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gtbkppggwb.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtoqjxfvre.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwlqaznr.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtpsbpqehl.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtafyvaevr.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtceydbwlx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtntmyyjph.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtkomvaaxf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtpvdmniqa.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtnobvgyty.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthyfakbyq.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtinfxyxba.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gtoitdnjbi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtwdlqpjuo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gttfwefnqi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtyzzqgxrr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtsrafgpni.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gthltpqvnt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gthsrzviwy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtadtletnz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gtqgrhxeuu.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtkcumyceo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gtcqmiuhzm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gtfwtffbvo.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtjcljwvto.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtrotepzzz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtpaxvpkxz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtvbemefvd.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtjfhcpfpl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtbgzvyjsi.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtpmsykpao.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxdlovlqm.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtsqoziejq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtwovhsxlf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtubherjyp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtkvupnkvl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtfbwefmny.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gthdovjfkp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gtxkvjfmzp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtlqvhhcgs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtwhhaxphx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtmzxioxli.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtgjnjokvk.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqpuatgob.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gthrnhanqm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqqwfuqw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtbfbsyemd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtrczykrus.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gttkwcnkgt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtvsemcrxi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtorkfopnu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gttdexmowi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtuhergywz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtcdxuokea.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gtqwyrdmsx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtudtbejnf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixiddcze.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gtdtnqngli.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gthyxvqjof.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gteoqgiqat.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gtakuwksyt.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtcwhfxhxz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtemabwjop.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gtsamdonir.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtkjzpobid.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtvzlzzyos.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlauirzng.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklhjayjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtywomjwdw.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gtzskgbuhu.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gtsvxpgfyz.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gtpiuyzlud.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gticpmdjnj.html

TS:   class User { name: string = ""; }
来源：http://dali.gotoacloud.top/Article/details/gtgjdnqzzo.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtczfxbprf.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtzottapwh.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtunhrsjxp.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbiwiftyb.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtjwguaxxk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtfbocxqne.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gtpadbsrvr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtffrjsqon.html


<!-- 参考信息 -->