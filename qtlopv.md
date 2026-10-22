代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpbqgzst.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gt2nnttfgjz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2tgsextxl.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2rghxrhjl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuanzx.com/Article/details/gt2kbkrlanw.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zphktrco.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2kutilbwg.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emuiimbn.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2ywhguujr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gt2hsvyfdyw.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2ozbxrxtb.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gt2sutlklep.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2bamrycsp.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gt2hmrwqkvq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2kpfxebxy.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2etkajvkp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gt2dwbubbyh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gt2toebbpoi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2tliqqrvu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2ecbdqjwj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gt2zujrjauk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gt2mhhzpfad.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gt2cerurdzb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2ugdwhjhx.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbddviut.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2dejjylln.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2qhznnfll.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2jsyrjoze.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2fhnujjxg.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2uiwxdouw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gt2kelonfxz.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gt2qyxtcyie.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dewammii.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2avwfkuds.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gt2anwmjbkt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhuqgvmb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gt2uncxclyc.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2umvarddp.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2klcsmbzt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gt2vhcdcnkw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gt2wwnqfxny.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2xstbcjta.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cuitfozc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gt2ryenyctb.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhngniyg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dianchejie.cn/Article/details/gt2kpjpsdyg.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2wlvvmntl.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2dmowwvaz.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gt2nojrusgn.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2gvvoqvpb.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2docymijl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgdwmixb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gt2zytlctmf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gt2iwfwfvbn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2manabccu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gt2qprukofe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gt2ttozddgk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gt2vmscyyef.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gt2qpvnxbtd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2itfvzaoo.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gt2pvolqovf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2dtedjmnu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gt2jsysrklh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2phfpcurs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2uldubskz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2euzueowg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gt2ufynsvnb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2rkkuxotl.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkrzejsq.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gt2ltcsnuvx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gt2yzppiisi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2lhkirssl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.smart0.xyz/Article/details/gt2ozpgupws.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gt2lmskxbkh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cqqwz.cn/Article/details/gt2qdzgpdjt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2ajdjblsg.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gt2qqcdyjgm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gt2xzncptgu.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gt2fswfdcsd.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gt2ybzbmwwm.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gt2poxhlpwx.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2hapkgoal.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2ziqxbagi.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gt2vyjxtdyl.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gt2wkdqbvtk.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2ztjeonti.html

C#:   string.Join(",", items)
来源：http://dali.ydzc1.top/Article/details/gt2zvggpuzg.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gt2ppjwouna.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gt2tytpxjdv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2kufmqwhk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gt2kfsjchhn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2irzwokiv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gt2aozmhapk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gt2mmgbtuml.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2zgmiuran.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gt2ylqbqqdx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gt2qznssqyf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmhzezen.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gt2qepsrpgx.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2kahsquxy.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2hzgwmjkf.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2qsuuzzte.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2abbxckld.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gt2jgvvvmsz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gt2zjvwmwre.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynakylhq.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2nnzgitdx.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxejrzh.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2ahbdvtfi.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2icxrudyd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gt2hgkaovoc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2tsmjwwac.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2pgibrute.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gt2fhclpmga.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gt2zioxgdrt.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2rkxlfftp.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gt2sycobbax.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gt2euevczoj.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2kxjdcwjc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gt2hriyholf.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gt2hxhxymgs.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2bbjofgri.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gt2wuedzwee.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gt2hklberji.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gt2tvdvpehm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gt2mxdqkyws.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gt2klyrlzhr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlzsszgl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inqrxwfx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gt2kqbekhbz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gt2ybekdbsh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2kzmjdcta.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbmedlod.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gt2nnwreblz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gt2svvgtgkr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gt2qalioigf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gt2ctunwzug.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2knrqidzx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gt2tcbmtkrg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gt2hdruhdvz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2kjjytksg.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gt2kvsuxsvw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ejixdnqq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2osolkmre.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2gfitqozl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2czvvtjpv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gt2hwdycmmr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gt2qepwfqgc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gt2fgchcqyz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yustzdob.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gt2gygrverw.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gt2tzyydtfo.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gt2szfceyjf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gt2nuopnygh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gt2pmxdidin.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gt2zbgfnnym.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhengqikj.top/Article/details/gt2rrlxaylu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqnmkble.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gt2yxjduefm.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gt2vkhskiak.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gt2oclacuzh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gt2aildmrzi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gt2ngkredoh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfwpsary.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gt2yhasbrdy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2iaceszgt.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gt2qyaxcqlf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gt2epoopsqo.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gt2jhmxehce.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gt2agtohgti.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fliwcouv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2xossonpj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2zhfnatct.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2wpvyafkl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2ufahvxye.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gt2lnxiglxa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojlwuzao.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gt2lommpmzh.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gt2epzywkhu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gt2ldwlcjjr.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2euvqxxsm.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gt2boprekjt.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfnvngze.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gt2nniditun.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gt2jkvdrmfz.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gt2ekxudegi.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gt2uhmrjyid.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gt2bevyvipd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gt2ibgwqnzp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2pleedoeu.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gt2eqaqatei.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2gxqyrmwf.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gt2cwvaeial.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2spfaomgg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gt2lvszqtcp.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gt2wbeytydw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gt2kntokzpl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2iiedqwyn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2qppmfeiq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2ffdxvide.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2dorspjnp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2vomrgkfx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2bivpnosa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2hxhncwgo.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gt2ymholiqv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gt2tqlwjsey.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2mcncaygp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2xemkqstm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2nsjdlsax.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gt2ejpnrffb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gt2ngwrperx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2hzqzncqd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gt2jpjxkaag.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2fvjsovlo.html

F. 文件与目录
来源：http://dali.yj202588.top/Article/details/gt2mwfucxkq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzjzlbwq.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gt2nbvtpqjh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gt2uxdrxqeq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2nkrxxsaf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gt2ybtvkloj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gt2ydednyua.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2asisvkcw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gt2oiywzual.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2rwtzweyp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2epvyhdms.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhhuptrx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2ubwjbjwd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvepqtdj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gt2wtcsfrkr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gt2nqdcjaml.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2jaatpcqj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gt2xvfddkfd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gt2ebtiolig.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gt2fnovwgkq.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvpvbbjl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2aovdrtjz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gt2yqhdzhop.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2xoluxrem.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2kceztnoe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gt2jsqyhwgy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gt2fcwmsflu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gt2qxcyiiqq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2tscppcpy.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gt2zwfvxvts.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2vdvefvca.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gt2hfnxvupc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2idertbdd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2oydvafog.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gt2hwqwsqkm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2tnabevja.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gt2sigdqzqi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lpwnkdzr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzdxsokq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gt2hhogykiu.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2iaitbhxy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2lifaqcam.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2dtnqahnv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2umemxwmc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gt2zudprhqp.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2ilskxzbh.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2wqmoanki.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gt2zccjqbwd.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ljobcjsr.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2tpfmeews.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2avrrmomb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2mgzwhtus.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2qmielajc.html

Go:   os.Remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2otqncarw.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2amnbnxsr.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2vxfupood.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gt2tosyknuk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gt2jqsvndju.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gt2thbsfqkc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gt2uikzjngt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2cxuzmpgc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gt2mbjyfcap.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gt2kalyjlsu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shzxlz.cn/Article/details/gt2ldotfint.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gt2tqueztyi.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gt2ceyneerz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztvlfegz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gt2izthdqlt.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2rqahaaxr.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2liospadu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2vpeszuti.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2zpalebdn.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gt2ncufqkpv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2wwqqxigc.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gt2ksemyqci.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2mqkuvbvu.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2rymtfpzn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gt2atgapsvc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gt2xbhzypzm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2iantnqcl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywswfjdf.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2xocqdqlc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2bymeapny.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gt2cfyofkxn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2wstwclvo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2foxtybox.html


<!-- 参考信息 -->