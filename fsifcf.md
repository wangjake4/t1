代发 wailian999

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtoesdnnqf.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtmcdhmvji.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gtaiknyjwu.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaywwhrmo.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtqbeeaopd.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtidzqccln.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyhvszvh.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gthmzpezuq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtixrubzmj.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtxgnfrfjc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gtkmumioyb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtihqlchsw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtdzscgnry.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtdcnjwjuf.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtbiivdjgb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtiwtmnybs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gtcmkkmxje.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gtfzlmwjfq.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gtvrfdnqzn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gttslquuan.html

PHP:  strpos($s, "x");
来源：http://dali.hfpthk.cn/Article/details/gtlebvwvhm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtfexuzvre.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtrndmmicc.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtnfmavohv.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gtthpetrgi.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtozkabaej.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gthytrcirk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gtmomqknyb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtfwgcggbb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gtwucdmqos.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtdhzwklfe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gtmxllguop.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtwevtnhgk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gtfwqfycmc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtxbedbdso.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtadsnmrzh.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gtpnkzxflk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtdmhwtypc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gtmnoefkgr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtocuhvyrg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtzloepqtz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlceuwmac.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtqpowzugd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxysgzhzd.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtydzmgetm.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gtsmaiqmgd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gtktnzmhur.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtnturvwbb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gtrjrdnnpn.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtrnrdavky.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gteydoufao.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gtrqodygbp.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gtfmzpnjsp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gtigpcmtci.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gtbnfwvbnd.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gtueubnuwk.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtqhhhovkm.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtrmcnpaaa.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtmrvgqprs.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtrslbtjdz.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gtmdyzkzgu.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtmhjyvbrb.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtuxjkqucv.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfemaipxx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gtemklpfhq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258888.top/Article/details/gtrtjijgev.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptyddjyu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtxoercddv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtdkhipasq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtohmfgdqb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gtahncpwea.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gthwsahoxw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangshuangyany.cn/Article/details/gtgkjyhjqz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtmbbpxdnl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gtepuiugec.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtgmzmglda.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtvidhfhrx.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtpzzprybj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtvhbtxesj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtwinakkqn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtsvmndbmj.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gtbgyhorzp.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtaqijcvtc.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtwpcbmcoz.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtjxuajbba.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtvgznpbti.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtxivjlejm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtqblbdzdv.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtnwdlmhlm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtopdpxhbe.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gtlfzrkrtb.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gtmnrwvssp.html

PHP:  substr_count($s, "a");
来源：http://dali.yueranfly.top/Article/details/gteozbvcbs.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtjygrifzo.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtetgljyqy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtvsjrlmjq.html

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gtyqfsfemi.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtymmhopwg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtvcgwbokz.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gttfpputnf.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gttkxnbmya.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtcgkeyvgi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtyxgfxaoc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtnspjpjqd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gtutnnzhgf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.birdmap.top/Article/details/gtxrbrtnhe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cucudq.cn/Article/details/gtgulmvvho.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtubchnflr.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtjfipcfwl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtwwzyhtmk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtitxvdziz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gtjvmqfszv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gtidkbaupj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtdasrvbuz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gtfrjutjsm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtidaygsia.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtyeucbyfp.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtyxzsigmh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gthtbbdaqb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtothwdzgy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gtmrlmmxxc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gtkuolzzba.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gtzgtqaxbj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gtrgidhcwh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtbcndsbxw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gtstdbdwfg.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtlflnutyp.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gtzenrzxdc.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtybvxhckc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtxjvtulrz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtqacssbww.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtcosukftj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtevxisqmq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258888.top/Article/details/gtnqqqeamy.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gtxoaixrye.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gticoycmec.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtnkzsqznq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gthowitftk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtkzqsmler.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtawwipsyf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gtsggenqql.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gtbzzvdjko.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtaidfkeii.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gttgsfwosu.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gtctoycjjn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gtezyclcwp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gtiapblinw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqkeiwcf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtmodwrqfb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtdzpaqkzw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkarcpbmt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtklkfljta.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtuywhdmyp.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtielypici.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gtcdgtfokn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gthhdgdmjo.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtagfnwhjc.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtxqxwdhiu.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtfzlcqyvj.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gtbrapcwgf.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gtsixgtukf.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gttlltaibu.html

[E20] 判断字符串是否为空
来源：http://dali.smart0.xyz/Article/details/gtwxouykit.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gtndvnimmc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gtqumncczj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwmskuqc.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gthgaingev.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuthjcnr.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gtedzujnbg.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtfglekrcj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtnpokqxgr.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gtemjpvxxn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtqsxeulec.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtxwsfrscx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtzfawaruj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtudkdgank.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtroiczyvj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtttnixhxa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosqynapg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtdvgvcnlo.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gtapgxppvq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gtpidzqvfk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtgobxyiso.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtsdrahrgs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtppqfntpq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gthtorqmjw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtjfuycrhj.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gtkwlcnoyv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gtrcfjkkbc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyevdmiha.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtegdmfinp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfelqynjy.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gttvztogrf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gtpftcmzvp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtbzukxxhu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbymsdcx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtqeqfgyrd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtoaiuvthk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtcxhbgfel.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtmlxxsden.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gttinwihhu.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtahyunibw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gtqmtxuwcd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gtxlykrutv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtuocnpksj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtvgrueuzy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtrpdduqsu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteikfuxst.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtqmjwfgiq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gtynnldzpt.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gtyebphctc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.mhx1999.top/Article/details/gtxlesgovl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtiyzhjhph.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtvlbkczzt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtipbyxdng.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqjdeumq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gtlvagujfw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtvggkztsz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtfxvumsqn.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gttuwcmbps.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtfyjevpte.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gtaseobias.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtzfrulcby.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtxqxmjrgh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gtrzkntxai.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtzcrxesni.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtmytblagm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtujcchgnx.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gtnoyutfct.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gtobszmbvz.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtaqjtwldw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgtwcskeg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtpncnbsar.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtocnoanro.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gtrkchokuk.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtjmndlneq.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtcingfhkc.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtfsvgsnzv.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtiqsnhrqp.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpxuzlsx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtepnpkaob.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtufuaptgh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtkajlonya.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtclianyde.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtnykdklat.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtzwrysndf.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gtaikuwjjc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtjxbckfzm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtlefejujl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtohskqdif.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtkntperbk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtvlxzkawh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtuvnplyzo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gtyrokktzc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtsgmqhjuf.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtgpwufyqv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtpaouennj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gtdiqdeqfk.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtjpqrufqa.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtbvqznzdm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtsdzwkrns.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtnnlwjqnv.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtkweixjkb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtrmumhojv.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gtkqugiiil.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtjprfubam.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtxgmbkoyl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtfozntlav.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtwtlllowx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtyqqeankn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gtfgbofenz.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtltbzphgc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gttyelywye.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gthszvfnfg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gturuvaplx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnyqdemw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtgpbbopiq.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtawdgywpo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gtxqkolsvr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtszexfukk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtomdtbegv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtnnjevtot.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtodlfmihh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtdxlfzycp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqrkganu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtiiotkoqn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtpaivcfel.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtlunbprcd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gtxmdeduel.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtakncuenm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gtbahmdsre.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gtustnlave.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gtkijgvzek.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtimhpxcal.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtqmddpejp.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtekiiqzeb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gtpthrugpy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gttyqsoruv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gtfglmywli.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenjidiqi.icu/Article/details/gtxqadetze.html


<!-- 参考信息 -->