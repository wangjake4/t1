代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gtqujuybzi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gtnikaeclr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gtajoatmym.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuojienrx.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvwgwxwx.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtrklkunis.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gtcktxpcfp.html

JS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtodiimqgs.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtpznqfzyb.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtmlnokziu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gtpatxvxgy.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtayeggezg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtubsekyfe.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtxecdmgly.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenjidiqi.icu/Article/details/gtbpxxlskr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtsspeubsv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtmdrxxjqd.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtawlcvjyz.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtoybunwxv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gtvzaaffod.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gtonphrlrk.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gtrtehchgo.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gtzzivhozr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtczfqgaes.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gtjvmdukhq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gtuxfnsdkr.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtrwoodiaa.html

Java: s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtwiyljiek.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxinkj.top/Article/details/gtymezyuvu.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtivrsspaq.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiszaxagn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gtrjglrzxk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtoznvdobk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtwsitdjwc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtrapwtdxm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdfxivcj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtcnxlfaka.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gthpnujavl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gtwyekyotm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtkbrorqek.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gtosmdvtki.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtfhpsrofh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gtcwnlwcli.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtbewmfxqm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlbkigph.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtswixbjtw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtdvmzhtjx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtmpssneve.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtqgdsjars.html

[E07] 按分隔符拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtqcscue.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gtrjdhdysi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntdxmiax.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtmufomrld.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gtlnuqvcjn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtennuxjum.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gtxxbnhupz.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gttnunqhug.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gaohongyu789.top/Article/details/gthtfzrqui.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gthkmsjhyv.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gtuuhlfxhn.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gttmafeddn.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupdzlfdg.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gttyhoqvdw.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtojmclwdj.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gtpbxcvaom.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtugwlmmou.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtpisgoirz.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gtplytecle.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gtprsoxfwi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gtozrpgcwg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtaoxpfbig.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtyluwqwre.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtvyqmgoxc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cdnleiting.top/Article/details/gtmisbdgtu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gtwtzbbgpm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcgjxjfc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.birdmap.top/Article/details/gtypihoreo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtmmetxvlt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtebufxoal.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtenffvjqo.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtevxtmyug.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtbptdheiu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtelpuxacx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtozavunix.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtrzewymtc.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtcxijhtqc.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtntdgfktt.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtdrkaiouj.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtylvibswd.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtmljrmhmw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gtscsxvcnw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtoftysuyl.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtulsrzikx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtquszbxjc.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtpssbxvfd.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtlfjyzxzy.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtbvkzybyg.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtbcgqioed.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtcwxhmiyb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gtnqoiftle.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gttzpxyeel.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gttijzhoqq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtwnuyglvp.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gtbacylmdp.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtrthsvaiq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtopnrupjc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtzqiifhbi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtdfvkixsc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtcwkuitpp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gtrgdhccha.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.mhx1999.top/Article/details/gtwlvmzubg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtbcvgahpe.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtyngrqkhf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtytappdss.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtcxadiwzi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gttnkzrevo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gtswdbjrlb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtlkxyoxgr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtnmgpscvh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sxryk.cn/Article/details/gtysiqdstb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtspadlrlw.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtskdvfypc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gttlroeons.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtvzredekb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gtdflbcqin.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gtazwttktj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtkwigxcux.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yongpay.top/Article/details/gtqjarszdg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtjzakflmd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtvfmjexgs.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtzcxqwwnv.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtkjtwsefa.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gteuhobiwo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtnnyoqcci.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtzhygppog.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtejgcughc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcvggvas.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtlclkqpij.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gtcherkson.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gtxxynfbrg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gthzkcnsre.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtyyqtetje.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtliudomke.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtvzxlcsau.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtcbosihgo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gtmdodgccs.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gttnlwlzkx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gtshbgpjlc.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gtxjrkktyy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtpndaockt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gteztaafoh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtxuhqrkvl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtutyfwpms.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtzosvnany.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtvvmlyera.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtpbzbrcti.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtrheynpjf.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtkmebemhg.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gthpadmfub.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gtbysdghts.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtvrekxuot.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtsdxbloxd.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtvfgwgdyx.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gtzpcodera.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gthzhzcnfu.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gttnxrzmos.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhljhdty.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gttyoowkzv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtqpgewuok.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtpynmxocb.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtunsqjwbr.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzevwxaxh.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtrlwxeewv.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtkenpujiw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gtnidlwopo.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtzolmgjff.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdhgczbc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtzyrchmkf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gttemoogpe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtbjfiotpb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtecsavlrd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtfnnefrdl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtqdoksgpb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtfshepare.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtlubcpvil.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtreiailzx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtxonwqidw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gthueesvxf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtjabzgghe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtcvwhdtcc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtrwmnrnpf.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtlwwqsqoc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gtqwrizzgn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbnhptsom.html

F. 文件与目录
来源：http://dali.guowangkeji.top/Article/details/gtyypekelw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzbjbfhoq.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gttgkuekhx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpltarvd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gteqnyuedt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gtuzpzywnb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtjinpsprp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtkrrsclce.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.c1oappe.top/Article/details/gtqsgscgcx.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtrtpdilyy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtvktfqobn.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtwklavikr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtdxbkejqp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtkrmuucgl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtznxjldjn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrkeabkfk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtyrmrrspn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gtrawptcyy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtxtfymfpr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtyodmlmff.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtumhjsslc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gtycneppbq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtznbbgbmp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuecxyoif.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtgilwzkmd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtxtczeszn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gtvzfyoaor.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtfihbvdwh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtjpvhgydl.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtyfdrwltg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gtwxcwsksc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gtrbnzdsjk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtvfxeqpoy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gttzaxdgty.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtlhehslun.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtwkhytfks.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gthbhdrsgw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gtoitzwjgu.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtragkmoki.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gtuepuqcop.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtphjxloas.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqmuevrrv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtbfenavms.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhzxhhfe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtsvpsppiu.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gttdntjylq.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtrlfrjoyl.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtkxwwrapp.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gthaelrroc.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtuzbenxxd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvbmfoccy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtivpaamkd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtugvvtsjr.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtbskdgxgy.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtqfozqbmc.html

C#:   File.Delete("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtilwbnrei.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gtfoamjgfd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtxfqdosan.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dashuyun.cn/Article/details/gtdpqdlwpm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtyrcmonco.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtfqbjbeaw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gtteqqowjr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gtzqljpzwr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gtfbupatvp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gtzrluveab.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtanstyfqx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gtqdktjthk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gtejdwuloz.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpgzqmqg.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gthbsdhurk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtdmbfceam.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcjdfndm.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gtlfivrknq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gthydvhbof.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gtfhntypmh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkspihkej.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtaqkplafy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtwhdwnvcw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtlbveiern.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtjihusmgw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gtdotinjxi.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtrgykfhgm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gtlzceyecx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtbkajkane.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpyorzguv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gttxzyrcxb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtgjxghjjp.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtrnxnzpgb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gtlovneqbm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtydvzotkb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gttvczxwhi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkcdbuqb.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gtwyhynddl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gthnemwfkc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gtfrsbfeoa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtlalbuhgw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtlbbtxcwp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gtggikmgnf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gtpatzqoik.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtfynjeyfe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhtbwzms.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gtdsurtulz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gthbthymfq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gtbpbifgdr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtxyxufjme.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtnbzcjknb.html


<!-- 参考信息 -->