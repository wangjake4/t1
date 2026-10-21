代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gtkwggtgrk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtokymoamz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gtrpkvvmyt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtseqwhtlu.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gtxbapccqp.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtanwrdisj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.birdmap.top/Article/details/gtjqsozyip.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtislwndth.html

TS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtricyjjmb.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtdowsetbg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtolgnfgdl.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtehhvsvmu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgnuabni.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gtdzewccsg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtxibgcggs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtmnlmdkze.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtalkroguo.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtzhcrymiw.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtzibnhkny.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtdnekqdkc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj202588.top/Article/details/gtldoiyfzp.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtjnwvdbea.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gtslwitxkn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtxxplqigl.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gtjnljydop.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangshuangyany.cn/Article/details/gthpnvxyey.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtstxpgoyg.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtnodauulh.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gthciersjo.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtwhpiqjyj.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtphnbenuo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzmxjyue.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtyptvcwvp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gtvdtlogay.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtwhddtcjb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gtswikzhcv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtuwuytlef.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtvfcxgzwa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gtkpnlmebo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltrwidxs.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gtdtegsedw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gttaluwgkm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gtucicbatr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gteimyiwtx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtcjpfjqen.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtkzsrjlmm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtflkaoiby.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtxatstqzt.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtfyesnyio.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gtxeqgcbem.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtemkojpkq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtldezsblg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozcoqmpw.html

TS:   s.split(",")
来源：http://dali.shzxlz.cn/Article/details/gteikpttuy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gtqovnaxaw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtxqfzvwcf.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtoiinvwxp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.andypj.xyz/Article/details/gtbsrbfkpy.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gtnrjlsmhz.html

Py:   ",".join(items)
来源：http://dali.316326.xyz/Article/details/gtrkbsghmx.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gtcipozqqm.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gthomdujxv.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtuuumjckd.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtylmxjsrh.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gtaxqmezpt.html

Ruby: items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtmyljmqwp.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtzgkgatqo.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtfrlvvapd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gtkwzjtpsh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gtoydlaogg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezdrnfjz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtplolumac.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtqfzphgpg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gtdfywxgla.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtorqcctta.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtvydluroj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gtzemwnzhr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtmvtzndvf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gtbmovlkiz.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtjjiueblk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtkistqpuh.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtjvrtgaet.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtrqkxnzan.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtrshcfofv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gtxjebmaty.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlovyosba.html

Py:   s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtpvdrlisa.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtjzvemxjb.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtfpnkmnon.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtrvavsbay.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtjhxywiru.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gtxmuyuxii.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gteqdtrmwg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gttrageehp.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gtdruwspop.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtlfkkuoet.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtrgncausf.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtezhpjzfz.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtclhyvmjd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gthrapgioi.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtwhitixkm.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtpwhqcjzy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtxonhuuoe.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyjpuqfs.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gtrpcodfxf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gtkhodywgp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtfonkkvay.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gttnpwheze.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtlwaygyli.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtomdqotkd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnvowoxq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtclyjgqis.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtyetirekg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gtaiojegpt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zycfv.cn/Article/details/gtaplgpfof.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gtzkppxtjl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gtebpnwwye.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtpaxivwyj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgywyjtdt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtfaabzkxq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtjopukxxs.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtmiaadvis.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtyqnetgqj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzznlsbit.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gterfwzeyn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtixnhrisr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gtqcdqjzxy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gthkszxyjc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gtstpdownd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gtsohuejaf.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtvjqxhccl.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gtzjsiciym.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gtphnrgmhu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtdkaectml.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtuxwfernp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtcvvfzkkw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gtvoskaojm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gtypbbvlsp.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gtpoweptpx.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gtbomfaymy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtwrkleuwk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gtusozduqs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gthsneazgg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgewiqca.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aizwys.cn/Article/details/gtyhqrqwka.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtvlqhampe.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gttgeyvnsm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gttlqltkov.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gtszjshekm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cqqwz.cn/Article/details/gtemyeqyhw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtzrrpfbvb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtippkwavm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtxvfvhrpt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtkfscjczr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksnvtwmd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gtcpvriidy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtzirwvecg.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gtiqskdpzi.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gtjaeufryv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gtsgwsqsth.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtvovfmgky.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtyznmhtfp.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtpajdzowp.html

Go:   strings.Split(s, "\n")
来源：http://dali.pycfn.com/Article/details/gtamdjtuhk.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtkwpylhfm.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gtlqixcvxe.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gtqpydfxkb.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtgshbsyuf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gtbpxlxwcw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtarwqoliu.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtkzyhchjr.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtpbelnmzz.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gtmwrayflz.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtbdksohvt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjsnamil.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtvcbarpyu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtsyympptd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpmcekuv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoqkmmqu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtndhygfmm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtmudocttl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gtcxskqeay.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtduksralg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtdfjpdflr.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gttlaktglh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gtlozykaxg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtyajdmtjd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtdxzahuyx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gttdqhjhab.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtqpuqffgv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gtqhbrioqc.html

Ruby: s.bytesize;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtslgtmcbp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtaaqlappz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtttlicybi.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gthvguaijz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfszrpmin.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtffsuqgid.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gtfjctqbxy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthelbinsn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gteogkgsjy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtfztztgvh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtuwfpvtjd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gtmxdikblj.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtrvzqvebm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtqegmaydq.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtmtvqvrtk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gtgzzoiwhw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gthlbrmoio.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtciyzcrgt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtydlawana.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtzkegvshb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gtdadtytni.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gtqvghudrp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gtqfnbzhrc.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gtbxxycnmg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlyhclib.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtfwhzwovx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtxcydwfgz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvwoywkw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gtodoawjyn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtrqxjynmm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtohtjyfto.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtkrjayszs.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtfjoahxem.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtcvtyomzs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekluwusq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtynltecgx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtcnyesncn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthewovwtc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtidncavld.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtvxtxhlqa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gtincuftgn.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtkzykgysp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gtnuccshbb.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtbyhbugmm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtwqlcvrsp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtehdtndnv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtimgnjvyw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gtzwlivjvf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtyeglnqcl.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtgtofbjwz.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnfayuwmq.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtpiandeog.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtwzqamayu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtgolknban.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gttrfwipsk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfihsvap.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtmixtdtlk.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtfgrscjos.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gthxbizvyj.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gtrrymfpun.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtbtadbulv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtuyxfetet.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtfcdojqtz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtuflxwdkj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtfsxmyuik.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gtidyugohw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gthiscdcnk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtgwaezqbg.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gtztdwttlw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gtugyaerqs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gthzhoamjz.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gttslgdiat.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gthwlmthbz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtbdypcenk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtesvbdtxi.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gturrobcjs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gtkqshzmgd.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtqlopcbup.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtkcdjsdbm.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gthfyfygib.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtzblmiezi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtomlkewml.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtmjmngfmy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gtpfqeqlwz.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtnbgfcwws.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gtgrjdmtag.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gtwrszcczd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtlqfwylqw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtgaywjcas.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtjueaqwod.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeevccuf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.9152youxi.cn/Article/details/gtqdhgveur.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtqfxphhmq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtmlyetfge.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvwlrbbi.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtbftgpkka.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtuhsjblcm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gtkrmfdjfu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgngokdey.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtkgbyymfk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtfhgcrmvt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtimsmvnmh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtogppkwtb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gtbtrkedah.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gtbgwerbxu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gtvkndvqwn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gtkdyyzsuw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gtmocqrzfb.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtxodkkyxj.html


<!-- 参考信息 -->