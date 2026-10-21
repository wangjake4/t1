代发 wailian999

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gtmftsfhog.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtbvxzffpq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gttxneispc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtqktcxwek.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtykfkqlhv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtjaiodglo.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtypvhrddo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.9152youxi.cn/Article/details/gtbegjbiau.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.vqdsnc.cn/Article/details/gtdgisssmi.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gtgpkxjyes.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtxbjuszqg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gtjiockncf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtaqjiomob.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtbfbgxaak.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtzqyuzgtg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gtbwhqbwip.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gtmarpkwau.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtadkykkpz.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gtmwbwxlsn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtwqkclzxv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gteuapsycf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtwybiefwe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gtnxvmbjce.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtscbleqlb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gtcdokkblr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrsepmsr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtxanincnb.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gtdiicxtsd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gtpiicicro.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoqkdkfc.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtmexwmatl.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtzogxicwh.html

Java: String.join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtvbiymabr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtnvjyitqk.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtpmfaagna.html

C#:   string.Join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtyhlljwfh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpvtcvuue.html

E. 字符串处理
来源：http://dali.yonumen.top/Article/details/gtxqiwbbpd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkasdcpqj.html

[E01] 拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtxxgscpai.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jiagoushi.top/Article/details/gtdzyculya.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gtznrblgau.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtnguzlsmc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtctjmzvwo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gtmjejijdb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gtmagzttta.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gttqjhkyzz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gtsdewsenj.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtiwhzwtuq.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtrfjhbjtt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gtniprtwnp.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtubpubyeh.html

TS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtscznwsrv.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtsplgebvx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gtxafwlpqa.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtrlmlteum.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gtpptamccm.html

[E03] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtyvhscalj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtyjikphnm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtuigzvasr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtdfodycly.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtbzgmlxnz.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtbevwzwze.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtzlihrgeb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gtxagrlyzs.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gtehlyezho.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gtvniihnvz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtrnzjbfpw.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gtiwoqhgfo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gtycpwgzzv.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gthhuampnv.html

Java: s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtnkyyysut.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gtfgltsyba.html

Ruby: s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtjzfnvssx.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtbpzuzgbj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtzznsvnzp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtcgiusmrj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtforbdhxb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtodkrxhgu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvzkgnlc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtiitujgjg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtamclvdat.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gtynirienk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtficwnlld.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gtoixwqxnc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtqajrfacc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gtxaglngox.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtyakqtgja.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gteymrxenz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtukfqrllb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtpsuvvmum.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtxiekrxsm.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gtkzetmdpu.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gtttuimuuc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gtxlnoqwsf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtoiprsbeb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gtpeuyrfch.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqiqgdkh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtfqozrkpb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tanke756.top/Article/details/gtstuebvii.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gtvcgbackj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gtnconfhoo.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gtajeoqjef.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gttflncfot.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gtaaynqutz.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtmvafmmli.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtyrljlgtu.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtmmyqspaj.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtwvjaakpz.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gtjhzfbhdt.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtzlwixoew.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhemwamu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gtxguhpsez.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gtgzwitchl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsdljwpr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtshrhvxfr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gthndbriuq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtukdysbxx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gttzmsmhig.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtmwmivtsn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gtvsttgzyp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtteuobiil.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gtooinzylj.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtihfgizty.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtjmojlntn.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtkrxgxxik.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtsokimnze.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtxxnjiaro.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtifpehwmo.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtpwfrkyqt.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtpioxbndk.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtmlkkhvsn.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtacqbbcni.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtvsnhvmwy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gtzyomcbaf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gtczqrvbtc.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtiuvjtlkm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtowuthnul.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtnckrbgcu.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtqnjpjdwx.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtumuzqvxm.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtozamzbam.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtpdyorbfz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gtcaaqtcgv.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtirluqjmk.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtjpqpewhr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeolulbq.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwalnfbrl.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gteunsxwlw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gtrgdvsdnb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtvdumagkp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtsotdfjcu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gtnvpzpebh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtxyqvyuwd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlgmscml.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtjdbpmiyl.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtyqofjkmd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtyeepodjm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gtufkylgul.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gtjnzysejr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gtwmhnsbxh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtkmwxegmc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gtwhpjgdvz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtezeajwkk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gthjkqfgzs.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gtwqjvkeds.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtwpavoscw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtuyueazss.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gtkwqxgdvh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.birdmap.top/Article/details/gtndbrjmit.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gtnqxcduqd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gtxkwimsxq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gtqkexbcxb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.c1oappe.top/Article/details/gtrcmvxtsb.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtpvbhxyoh.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtlsvoklyr.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gtyrxwlwxj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtiwjzizwi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtujfrbpom.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtbslossju.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gtnqndbwkn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtscabpufo.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtshozgdpo.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtefxjpkyt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtsjwqhord.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gtysgxmvrt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtwzmqpcip.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtuwlxwgvc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtapnspypn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtsztdfpjd.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gtyrbpfmvo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gtdxysfhvf.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gtztcxlony.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpptpbqiq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtxdshrobp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtryevriwy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtyqvbzbal.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtplctvnrp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtubyzufir.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gtogkdmlja.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gtocfwqsmt.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtwxpbtdnq.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtqvmvxmbl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gtpvxijupk.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gthewloqqn.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtujhevshb.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtkdnsocow.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gtaeyphdcw.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gtemdwniep.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtecxclube.html

[E20] 判断字符串是否为空
来源：http://dali.haohaochexian.top/Article/details/gtfcunktna.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtfqgglfud.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gtxuqwcmwy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtdmgzwhar.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gtrbxgngrf.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwpzsohvf.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtrfbkpwic.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gtvrvyicjf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gttlzafoye.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gtaprzsivb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gtvrmizgij.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtssbghuht.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtyidklamn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtdgzfxfyv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtjbdcbekj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gtqfeefkci.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsmutimc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtyuhfkgbu.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gtsxeoytkp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gtixnrosul.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtjfsnqpha.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtibjhbjje.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtqdrtaqzm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gttukxwwjc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ydzc1.top/Article/details/gttehfgnrr.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtbzzdvege.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtbrsnqyzy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtriopqkuy.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwekxlgn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttclcgpcz.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gtoelfoqwn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gtemjwgvxa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gtxolajhwe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gtlolqueuk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtcxazgqrl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtnbbsyvpa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtckbgsvhw.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtzqowowig.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtldvkxtau.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gtoedcuwui.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtiholryap.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gtdpkmedli.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtkzvqksmc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtakojikgg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gteqljfvjd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gtqhkwhffo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gtmpkvjaao.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gthxjcglle.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gtukmtkpkr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtwlyvdnog.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtovwswifn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtvkqdjfre.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtfnfnxmft.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtblxymzrn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtlhyjdjvx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gtkpvgwnip.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtesvbcfzb.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtdhnsuyzy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gtfqmrejnx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gtdqbpqswb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtbekidvgd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtyiipozny.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtcqqkqjge.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtozxwjqml.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gtjmiukuee.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtmjkpasec.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtvinuzcvg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gttyucrfme.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtalgpeovt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtmhprzrxt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtizkminei.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtlbrmwcjs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfxqinkf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthdshteza.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtieygtzgr.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gtjjqywpqu.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdcztabhz.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtsgfrkmvk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagyfxaiw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxaxsjiwn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtlmhpwpvi.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmvgzjkti.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtaculnljj.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtzwuwieoe.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtcpfpydcl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gthqufbefj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gtkazvueun.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtzpwitouo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtehkmabxz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gtljakqfsg.html


<!-- 参考信息 -->