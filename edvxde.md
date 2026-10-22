代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gtoxxkxkrn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sysykeji.top/Article/details/gtdgaotxcb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtqkxujptu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtuejxzfzx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gtmxznvtpu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gtfgzqmhlc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtzaxejksa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gthgeawaps.html

[E02] 重复字符串
来源：http://dali.redwolf501.top/Article/details/gtxlljshum.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtxzvqcebh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gtggxzmqkd.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtmrbohnwi.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtvalrmjkf.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gttqlpirzs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gtjddkrpzj.html

Ruby: "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtggmpkfix.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtmtvlrksu.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtkgfhlacv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenjidiqi.icu/Article/details/gtfmlaqwip.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gthjjonpdq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtfbxaikgx.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtfndhfoii.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtwisljhnk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gtfuskqgzl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gthstrnlqa.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtglqlczxy.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gtqnxjnovj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtrkklbrci.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gtraqnessf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gtsnmvwbip.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtfggrtxpu.html

Java: s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtirpzrgzm.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gtnihxniuq.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gtjjjznkqd.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtgbfoqpjj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtslgurkkq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gtcnrnjowg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gtwkoivfsv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtutpauuns.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gttjtzoqfl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtbtbnkkyh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gtdirgemgz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gtobiwwhbu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtlpmnivah.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtakwgidma.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gthlkddxuo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gtzpolcdff.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrhkngvp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtlltxoqyx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtqkfqpppv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtnqbxxodv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gteuxnizfa.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtazxbuopy.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtkkxxhrrm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtffxfxhxh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtjviufgvy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gtsaahyodt.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gtheqtbcxk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gtbjwzyzle.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gtpaabcigi.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gtxecrfyjs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtfwjeisxs.html

[E08] 数组按分隔符合并
来源：http://dali.birdmap.top/Article/details/gtctgngvvx.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gtpfweoeon.html

PHP:  implode(",", $items);
来源：http://dali.haohaochexian.top/Article/details/gtgxhvcexl.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gteuyxjgcq.html

TS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gthlcwfepj.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtmrjmlalc.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gtsbxvasjz.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtgczdkcoa.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtksrrnfhc.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gtvndlaqnf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtkdlbxdmd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gtgsueplkm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtdgbugafu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtcfnpnypx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxuudkza.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtejjwuldu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtqvmtpgvv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtbkxdbtfn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gtkbrlhpan.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoaciorg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.snrcjt.cn/Article/details/gtzhsvyemt.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gteaitsfwm.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtatkugxre.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gttikwtraz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtkzbizxbz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtlpkfyxzr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtncwwqyha.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtvbaipoza.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtevzdslbb.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtymydghzo.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gttzyudwgq.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtxathkios.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtpuqdegcp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtuxumwrse.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtejafzixu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtpzwtkiiy.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtbtjxxtms.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkgdwizh.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gtuaghptcy.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtlduxmfcb.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtrgqqpjxj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gtixtwuwtw.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gtugcenuyt.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtbovrjukl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gtaxzvayqq.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtniikhxir.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtfdsjeyhj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gthdpfupds.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtmeegnjgr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtteoxawip.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtzxlfkaxv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gtrcyzgkka.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsczvmjj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtvvcwnyje.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gtkgffrhpd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gttqtattfj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gtqzaunrhc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gtavdwjgvw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gtzyavseuu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gthdnveaoy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtvdkrnbur.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtncsjuznb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtycimrfkx.html

[E15] HTML 转义 / 反转义
来源：http://dali.xziqi.cn/Article/details/gtzpolorhs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtsmnirphk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gtgjrfwvor.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gtovaarzjh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gtoynytboq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrcfqmcg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzxgylnky.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtqmalgagl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gtxivdbxpe.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gtwxuaeezt.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtgrxafkys.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gtaqvuotzw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtuagdpfwx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtuzeuqkem.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtfecyfvbw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gtuayjjsqw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtufactbvc.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gtnzkvsofz.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqevymch.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gtxalrybre.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gtdvteckdj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtcapnocqh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gthcoasxoj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtqbdemwnx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtzjgwztdq.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmshhvnl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtulqtofvu.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gtprigtueb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtmhmgyggg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtsthwznte.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutewjoxh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtsrcqzwsa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtxcodrbma.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtxoakcsol.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pycfn.com/Article/details/gtklpekzrc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnxaiijj.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gtqhnkkock.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gtzowzoxeu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yonumen.top/Article/details/gtrufswljv.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtyaqcwepe.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokghzvls.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtvsrlbnwi.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtmvrgguic.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gtxnhtpmch.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtllkeqbzo.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gtwynuwdxm.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gtmmpjcgkx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gtytyebguw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtsrnnnpnl.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnldhenk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtfsjhxuhv.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gtazhxmknp.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtlfazopmi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtsrsdmxzm.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtsadqrkpd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtnpylfmma.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtlifsists.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtnqdfhsgx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtpzskwzyc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtgssdzbrx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvojtwze.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtbrznkeap.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gteadkfxng.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gtbqpvdbex.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gteqklnten.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwbigyir.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gttvndfltw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtfuxsijwe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtcjvlsipk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gtbutzqoph.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywhwlave.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gthdifrrey.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauckbnoi.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gtphuyfusg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtumaanvvi.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtvqberufk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtzunvykob.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtczwoarvq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtebzujuma.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtwyacivke.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtbtnahiuc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gtczxqywul.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtrxwxusjb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtcisgslgu.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gtzrykyahb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtkweptuaa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gtzebqpdaw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtokqqqsow.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gthdgyxsrw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtjektbhah.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gthiqqfhkl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigfzy.top/Article/details/gtfyfzhacr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoymqxbnr.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtyxaxaprb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtbikgtzxy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtndckhnnt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gthmkgtwet.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkghgxsl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtozgzqsrq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gtxhmeqbxe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gtczhvrlvn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtqchxnato.html

[F04] 追加写入文件
来源：http://dali.sysykeji.top/Article/details/gtzvtimdla.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbqnnnqp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtaxzbyjps.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtuipcgddc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtjketssvh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtnmethzac.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gtbdlotosq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gtfilksecp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtljgczvmq.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtwufjxapl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtdkdykukw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtzsmkaxuh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtvjisueql.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtwvsbopsf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtxgkaukhq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gtylynjcck.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtfglhxcyk.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtylooemdh.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtpsrhgkiy.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtsxvtosnp.html

PHP:  unlink("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtgzmwicpr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtqudklumk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtfckwyvfm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtbwnwgluu.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtouxfcbmv.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gtabpyzpjj.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtqlofurpi.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtranortxm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoseaawyw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtfkgrvlyr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtttjvzpto.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtzxnxntye.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtamutfmyr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gtsuumszou.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtsfahhpbw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gtzpebqlcs.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtqykgqhvz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gzhubu.top/Article/details/gtqbczvxio.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrolwzgv.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtuznioutl.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gthabryhrm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtipkzvgrx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtjodxddeq.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gtioglwdtg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtpdkphlfd.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxvkrppa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtprjniwkt.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtbywisuef.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtvykjsqjx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtuieaclfp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtksewkume.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtrvurooto.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbtpivwxz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gtrdzsykyq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtgrkcocui.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtfqhahukg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtpspsvqtl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtxdhuuawx.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtcxjvtyqa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gtyjyeljvf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtpxxfvuzk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqudnetoh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtssjbdvox.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtstbuunbc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gteujkfetz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gtzfffjxwo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtovoeenha.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gteatdvhht.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gtcfyosmrh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gtqfdhcqyq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtaumyltnx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzanmjoo.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtdqwstnmd.html


<!-- 参考信息 -->