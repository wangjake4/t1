代发 wailian999

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtbqnncjtr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtkmbexfqi.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtiqnuwpuz.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gttzhxmcxh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxrzcetcf.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gtsjgeetmg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbumhdhdu.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtsqhuieqc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gttscptjvt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gtzsuvpkzr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtbkuiaaux.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtshzwxknp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gtatoglmht.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtynvkhysk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gtelcfmpis.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtokbbgagj.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gtmddiunkz.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtruzawhcu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gtmfvfemxo.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtqqofuseb.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtkokbaxsk.html

Java: "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtkeprszza.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtvvbsqirf.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtbqcjvfxk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ehwqpu.com/Article/details/gtilrjyqdy.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtxepsojso.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtallynzfh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtadqofprj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtzannmzrx.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtnglxyroj.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtrxlaqmfk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtzthyxqhd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gtuushfppr.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gtayzvaeox.html

[E04] 查找子串位置
来源：http://dali.gaohongyu789.top/Article/details/gtcaxsnlmg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtqhfmwsuu.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gtkxoxlqcf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gtzgszkfiz.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gthtbgtzdl.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtvtbzkvti.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtnjiwjuky.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtaoghkwzg.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtfvypnubr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdqqsoxn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtsmzlvwbr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gtjmnihfxz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtbgxpsqtr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtyvyukpcf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtomiwksak.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtafreyxse.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtezlzenlo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtyetkgyya.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtgldkabeo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtvzdlejhk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gthtdiexwl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtjdjgziec.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtnaqhmcmb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtrhgzlcig.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtshqvlake.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtandjsvmq.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtdrojrcfc.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtfbyqltdc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gtssazjztl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gthfgcscla.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gtodkwenez.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gtuhbszmfl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtyzzbwfcd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fzhhl.top/Article/details/gtmuxxjjia.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gtuyyvdevc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gttiecnilq.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gtbjrdruey.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gtolicoaam.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gtmgfyxina.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtabwvckds.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtuqthmqyi.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gthohznqwz.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gtbubczaci.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtkczswowh.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtnstvlqin.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gtbvpbiofd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gtwuupejgj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydngclrc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtvzqencmj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtlequdirm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtnnidmuir.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gtfplgmcxf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gtlabgdqxu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtfnhtlxch.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gtgkzahbdk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtgkmqkcuz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gtbdkgtkwe.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtxmiwlhdn.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlivgopxs.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtmkykxvdi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtifnyruvl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtwxadgmsm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gtifeefbnc.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gtcqnljcwo.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtxfbheclz.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gtlaahpjfr.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtxgxjnvou.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmzuwpus.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gtfhzrrboy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtzcaqpyuz.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gteyzviosn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtyjypibqt.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gtfutorelk.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtanxdvbvv.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtvtlmnwik.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtzpvtcuqz.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtjyqgjpzc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtfzsebrhe.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gtycuxvocp.html

Ruby: s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtocsivyei.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtunxnsdap.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtmbszoyfj.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtwkojekst.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gtuexwxehi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtvuhukiiz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtdxduwtxr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258.top/Article/details/gtxkqeqrsp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtcuwamwza.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gtntnhvtfq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtczqfhjiw.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtwmvrtuwr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gtuhgbllrm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtmrshmzvy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtolahvunh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgzvqlocc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtwznoxbbv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ydzc1.top/Article/details/gtzobtefsh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gtsiuuyzly.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtnalvwufw.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gthuxzxdrn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gthovohumh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gtxttjldwi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtqlegglyd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gtjkgphjis.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnarozukj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygwgtqzt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtfvzxctzn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gtgqoblprn.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqincfwqw.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gtkdjvjtjk.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gtjalzikuh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtnlifprhy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gthwrjiyhi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtxyvhfhil.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gtvxdcbbsk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gtamiuevhh.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gtddydzupw.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gtjpytxrah.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fzhhl.top/Article/details/gtuktoyrfw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtdbmtdcct.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtgehdqrnb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtzjihiisn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gttwjkvtiq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtkycwfjiw.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gtzqkpzfjd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gtbuujyjrl.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gtfdjxocnc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtxorxwggh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gtdxufwoxo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtcoadrqre.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtdcpcqomj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtqceacybz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtfgvbtifk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtrdsxypwm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtmaainwtb.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gticvvialk.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gtvqwdxduj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbkeqzkdu.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtldbjbxim.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtclvocjod.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gtgqzackbd.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtnqdbkbnx.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtmadrrazk.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtktludbtx.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtthqbipwt.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gtyiqtkxzb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemtiwceo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtrxatezho.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gtisvlljyi.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtwwkyyyks.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtefyibpsu.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gtxiwvedqr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gtlmytaobm.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtccfiysuy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gtygovjems.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtdjxatwlj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtinqiciwi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gthhdnzjyz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtljihjkba.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gthkidaxcd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtpkwtzfmf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtlqaufdsv.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gtcuihnkds.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtqvizante.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtbpfunaju.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtakwbejty.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtdbofrogo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtozbshrac.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtdteconah.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gttlszseuw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtxvkqfrgs.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtkyhtorxp.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gthtbwizlj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvyxmklin.html

[F01] 读取整个文件
来源：http://dali.hnqzz.top/Article/details/gtgkxqzwnz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gtedrqehqj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gteyewtafw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtectaafkh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyydofzd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtlndjiayd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdfmvyyq.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtnjwjayfh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtppqvtsop.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtmkvndfyz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtsgpyjzfh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtinwsolox.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtfcclnevz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtzogxrpal.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtnpwrnjts.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gtbyyswjpw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtmcxycuqb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtzfudagxk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtewguextx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtvhlluzij.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtupnfqfwu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtqielnrji.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtzvvgissn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtqrbhnazx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtwfmlsmag.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtitlwaoeu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtuklbyyjb.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtwjlauksm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gtxavrtqvv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtvcfnywpt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtaedhenlh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtvlvmnleh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtbjptvcij.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwigsoqli.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtqrlaflbc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gtiszmaeus.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gtcluonhbc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gtbsgdbhsz.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gthvyszrqw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfepmwecm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtpoovxgai.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtdmwhddzq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmncouxx.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtrtoafyhh.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtskydwrdw.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gtdhetkrrj.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtbmadciec.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtdornhyqj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtmqoimpeh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtujdcqbee.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtpiozelar.html

Go:   os.Remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtaogtlefj.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gtbaabywyq.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtjcwgneuf.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gthmiqiuot.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gttmyfhohk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gtmcauftca.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gthnkoycnu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtomriotup.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gtiunvckbm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtzarzxpzr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtoiypoput.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gtxowkhuhj.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gtdninzsuf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtvbiozumn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtpwrzawwf.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtyonkxqrq.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtmulaixip.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtpudyxmyv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gtgmesxynr.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtiwbycajb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtkcofijfw.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gtndfwiofy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtlnlzlvbq.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtmkyyzvqn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtpidadmew.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtdsskwwtm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gthzttozle.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gtwoziqmfg.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtvxnqmwuu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfkejsop.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gtmxwheumi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjoufilkg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlonsougi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgayygyuj.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwydhqvvy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdjelehe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtngzqexne.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtdsolizfm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtysnoteln.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gtcxoasnvf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtuncwikwn.html


<!-- 参考信息 -->