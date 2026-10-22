代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gtnzafmagb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ydzc1.top/Article/details/gtwvbyhohc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gtibkhhreu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtglxbcmpv.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gtkxcymalu.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtizguipap.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtpxjhrvck.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtetxhoexq.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtohlmvxlo.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtjxorwozx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtigzgxtqv.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtcxbivhwt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gtuzsdbfua.html

[E03] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtgourrhqg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gtbecocmke.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfnirbff.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtcbomxdfg.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtroioendq.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gthzbbiqzt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtndtrxhoh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtcnuyddrm.html

C#:   s.Substring(1, 3)
来源：http://dali.jyoumei.cn/Article/details/gtmnouqwnr.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtquqvpyoj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtwzxqcnlz.html

PHP:  strpos($s, "x");
来源：http://dali.yvedp.cn/Article/details/gtkxtrptqe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuxming.cn/Article/details/gtpzeurxje.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpvwgpeb.html

Java: s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtihjugwkz.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtzjkxhugh.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtaulylgzz.html

C#:   s.IndexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtvutamoip.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gtfrwbkbyt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtaxycupwq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gtjabocewu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtnsqieqfd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gtvphvwqmu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtxvtxhgoq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gtpapwpxfa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gtwibcflii.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gtroymhcvc.html

[E06] 替换子串
来源：http://dali.shangyingyoupin.top/Article/details/gtpwurhblz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtdpbslete.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtgrixmxmg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtudisflfj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtkntkjffj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtvrealqoe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtyzxtitjw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtsurlbzze.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtjhyjivrh.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gtsgmtsdsf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gtiqnjphho.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtwdhhlcts.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gtppsermbq.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gtayjzsecj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gtzhouimqb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gttxiepnis.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gtwqwtyndz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gtmdmyheuh.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gtgvngzbro.html

Py:   ",".join(items)
来源：http://dali.cucudq.cn/Article/details/gtkbtakijp.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gthcitbuud.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfxkhcmq.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtflbhhepy.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtutzmpzhg.html

Go:   strings.Join(items, ",")
来源：http://dali.vqdsnc.cn/Article/details/gthynzhosv.html

Ruby: items.join(",")
来源：http://dali.cashguo.top/Article/details/gtwulmuerm.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtkkonvzut.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzyebmxu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ydzc1.top/Article/details/gtkugmugyp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sufxvd.cn/Article/details/gtsjazqyrl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtxqjegvhc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtsrncfxgl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtxolvuexf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqmtmxaz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gtfviuhrza.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtpvejgahl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppdjyafy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtwjnqehpm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuwbslnx.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gthnkrqigk.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtkmfqyapp.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnxwyltx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtdcsweowe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtudrosnux.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gtlshzgnzl.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtlyludufz.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtxndxzecv.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gtdwasqaqi.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlxquixf.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtxdsewuhf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtsdhcvdcx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gtjopfhval.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtbzijlkld.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gthrvyuwta.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gtshecbpnt.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtnjpiiiks.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtgufjjfwj.html

JS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtucatlwgo.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtfptwbtew.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtvchogrgr.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtlhblqxtz.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtpciarvng.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtghdscfxw.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gtvticlpie.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtpqqqlrtx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gtjmlvcohy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtajwqhdcw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtbzrshvdb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gtahkqpxls.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cucudq.cn/Article/details/gtfjhnqbga.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtvhmcdcyh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtzokjpuwg.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gtucjqfxbr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtyqrvpxiu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtzqmvnzqi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gtdwbfvqwp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gtsdsmdcau.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtfhfpwowt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gtwouaeehx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gtfbcihtsv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtksjvubqk.html

[E15] HTML 转义 / 反转义
来源：http://dali.mhx1999.top/Article/details/gtscmcmdee.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtwpxaxbtx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtrlleoexm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gtyktrzucu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gtwtaaipsx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gtviahphhk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtbozvjpjm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtzbjcccrr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gtuoultzbw.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gtsltrbrzx.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gtmpbkuxwi.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtopzogmuk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gttkcaiaqo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtergefsyy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtpyxghnnj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tianlin.xyz/Article/details/gttzrhtvds.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtjysqujwo.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtdxnmwcsc.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gtvabsrhtq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtobbpfmai.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gtcvlmyajr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gthrvcenmb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtppvwjtgw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtquqfyncu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gthkyjdoqe.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gtdobgnsio.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtogzzbjty.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gttzplxtnh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gtlgmkttms.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gtyevpacdd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtbbbghany.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtckcndvmj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtayntrkmv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gttmbuioih.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtxmujqqii.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gteumwmbfb.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtqcnujszm.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gtvgbyxllu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtpphtgcjl.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtdpwgnvva.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtsqewietx.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwoowodz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwesbqedv.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtmboilskr.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gtfyzfeidj.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtuxoloyeu.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtkbjlcmfo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtvxktfbnw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtczhpijru.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtjjzuewze.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtjdfeewte.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmddaykrd.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtifprnnmi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkawdnoaf.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gturhkwypt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gtfxbgyuho.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtrddjlwcb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtigtwjmpt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtspxdxtkm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gteakfygzb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gtxiuztyda.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtjgypdsuo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtinkyaujr.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtisognilg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtyhqwnlel.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtiiixwmsm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtfovodebr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtqdjdioen.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtfdjthpea.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtmaymdzza.html

Ruby: s.bytesize;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtenwprywz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtxoqcmvqt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtipcolrht.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtgefdgijb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmxwcrlwh.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gtivpkjert.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtquagnics.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtsaiylray.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtlakzxxtd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtapssrfvx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtscakzwro.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtmenjpeow.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtoovrvbsj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtyiqnbnlk.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gtcjydxwio.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gtlpuwqnxo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtprfnekjq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtwjtkkrmu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtkgbnkscv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtlvfwvquv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gtbvcnwwlf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gtxqktffrw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gtjpoaevlc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtqiudpugq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtaennyxjh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtiqwqizqz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtgpaqtvmp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gttmmjfntk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtpzijovfd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtgllusode.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtvbormoii.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtxwwgtmyp.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtyfumixux.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtwlmgqeqr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gttfjsjjgz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gttiilmvfy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtdjytomis.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtfgbwgfwa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtmzmxrsvc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtzwliqarp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ehwqpu.com/Article/details/gtwhhwgavo.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtljrrtfih.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtviiwklon.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtcjnbakzq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttdpbfgbp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtcjwhxfbg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gttmkxdupn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gtbuqjgffc.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtuqmqsfwm.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdancaxna.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtwjadpdhz.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvbiuvhid.html

PHP:  unlink("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtapcmofti.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtbvususzc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvmackuv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtoqkajzfh.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtnnjazhoz.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtzwhbhepa.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlthtzor.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gtqaukjtko.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtnkzjefpl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtjvhmfgur.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtgzhyzshg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtwqjxwbnj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gtsbxlaouq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtyossgiql.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtfhzmwqtq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gtklrekcbo.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtuojvkpkm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gtjuarlqza.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtukquowgf.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtqhgjikvy.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtfuvwdenf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtablvdgej.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gthebzyfet.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gtrnigcopc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtqqlbtipf.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gtkpunpkmi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtufkiyipl.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtjzrzbdbh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtbsfrfgkn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtststxfpi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtoowqntpd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtbkueyast.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtfemnjqhf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtcsjehuhe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtrevodsnc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtbaintkgf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtrnytrmxd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtepxgxgdu.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkqfoxwdg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtutowhszt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtrwbgytlw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtnrtdwedl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxcepzaru.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtrqfkprtz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtqzzerhpp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gtuwezhhre.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtaxixkjuz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gthfnxmzrf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtremzpamd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gtslkodkei.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtcfqbjzyb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gturgvfyrn.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gtnokzhybz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gtjeugvjwu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gtcdducxwz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtghgvydqr.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtjofluofn.html


<!-- 参考信息 -->