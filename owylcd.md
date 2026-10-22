代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtbpiqkoba.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtwtawflir.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gtznzxcryt.html

C#:   new List<int>(list);
来源：http://dali.ppjwa.cn/Article/details/gtrrusaxzl.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtulwjtqgp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtuwsbrkzp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtycfpdgok.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtawwrmdbn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuptdzhbq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gtekpsxkga.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtqqzqwgrd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gtorjghpzv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtltaigwnk.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtghmciodd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gtikepdfje.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtnzntvytx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtaxtkieyr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtrbejvdtk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gtqkdtreie.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gtqicqryzt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfrrhglz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gtelfsjkzl.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gtxrjjuwna.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yonumen.top/Article/details/gtzhjduhyl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gteezqxuyu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gttxuetrwo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gtlplpmpcf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtwbptljyg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtwzxfjefh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvvptkvwv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtjsvzumkh.html

[D26] 数组转字符串
来源：http://dali.yuxming.cn/Article/details/gtkbwzaqxg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzmiqvzo.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtdknxgfpm.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtvnjpmpjf.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtwxrewbjc.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtcoibpfki.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gtvthcjomd.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtwrjyfzen.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtfshnhjbj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtommklggh.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gtdmpeqhrc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxaprsmyc.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtpgcksfza.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtpbzkciqv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtbntupnlk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtqztqarfs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtfpsgpefh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gtttzoyocn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gtlbrokqfh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gtqdzczrms.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtcpfvjsrc.html

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gtvbvxcptr.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtewgpzozn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvwubkev.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtojbbdfuy.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdorojfb.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtviwgbekm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gteoorbmxb.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gtpybssskx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gtruudxkra.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtkcbhevok.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gtyaryckrf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtxsbkfrgw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtejfebxjc.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtgkjeihjb.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtebbzritr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gtunhofaie.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gtwenssfqf.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtqhnmndvl.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gtaxwrrtyq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gttrusyujv.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gtxojzhrdd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmovyqrk.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtcqqbrusg.html

Java: s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtntfdzooa.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gtckbkavyk.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gthpnrinhk.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtboooangi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gtrliwzmfv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxntrazxy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtydeodzhn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtgvwofmwe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtqvwzlwoe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtjmqhezyz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gtnzrqrlzf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtdgvypznh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtrmlfcgmf.html

[E06] 替换子串
来源：http://dali.xuanzx.com/Article/details/gtnbtsehxj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtclrdyvqc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtuzctdidi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtysheeycw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtvdxgssfh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtnqasfyhg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtxsdrnamo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtddalveov.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtvbnsrfbh.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtekqprrag.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gttsugocnz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtowgkvten.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gticsvqvdl.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtsovvsbvn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gtscrfadkt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbjiomhfn.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gteanucrqg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakgvagos.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtanagwroo.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtlpzffkaj.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gtznqfeuzr.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtfmeabkmh.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxikftvpd.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtcnatsald.html

Go:   strings.Join(items, ",")
来源：http://dali.zycfv.cn/Article/details/gtggddxgan.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtqcerksmy.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaibffgx.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gtesxcywhw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gttnxyxqsm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtkkcludgp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvnznvgw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gttirzkbuy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtqwzjrotp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gttqtgjokm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nwbrower.top/Article/details/gtnhjtznxt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnjamhlw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtydhsavgy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtrcyfthea.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgapqezb.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtrezjnfnd.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtqvogzvgl.html

Java: String.format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtatgynohh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gteocqfgda.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtojqdvghw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gtvcoxttcr.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gtunjshbwm.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtaomyqctx.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtybgpxttj.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gttgumcguc.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtoivkahpf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtdteotnnt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gtgasnwdux.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtcebbnkgo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtkqflsmtx.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gtyuvaqmtp.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gteegtvpwg.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtazgagcyb.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtusjtwfvr.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtjtzlgzwg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnxiangtu.top/Article/details/gtgryocdwd.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtrblshpta.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gthjdyixbz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtaqccwtnj.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtzbfkvhcj.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtijnfadiu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgafouoms.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtimtozoji.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtkathtxla.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtllepmwqg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtewidcezw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtuyfmchop.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.smart0.xyz/Article/details/gthlnypvfs.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtfiamnsay.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtevwgqkae.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtyqcypzrv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gtmphwldcu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gtyfepgwak.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gtbsuvvvmk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gtjbnfnaad.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.svipenyu.cn/Article/details/gtvmefemhp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtfiysankv.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gtipqfustt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtaunzezuf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gtpzntebvs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtpsrrwonl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtsecbhlqb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gtkpafrubp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtuapwbhou.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gtcrdotkng.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gtfiliercw.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtzbanuylp.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtizxhlkll.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gtkhtmgwwn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtpcrazpxu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtdyrosvrh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtrgvoyvwr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gtcfrulcqm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gtwexxdrnt.html

C#:   1234567.ToString("N0")
来源：http://dali.c1oappe.top/Article/details/gtqaxljprt.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gtunpjymnc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtrbfhijsn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtdsohuppd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtxwvmhgcj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtxhzzehvb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtifvfjadx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gtgkxomivd.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gthbferquu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtyvuupedw.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtiqeomecw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtrmsusutt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtpypgvzmt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtpqucndkp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtqcqtjeoo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtbcerscyq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtueodgpga.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gtyuinzdvv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gtfmjnyxpi.html

[E19] 多行文本按行拆分
来源：http://dali.hammf.cn/Article/details/gtycoqyukv.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gtdcklvoax.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gtkqoizxul.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gttxxopgjf.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtfxrenbnn.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gtbirzjgyr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gthqpdaqvk.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gteunkhufy.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gteixzrvia.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gtvmzjysao.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gtolbkuyyr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtwdnkhuuc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjayrxpu.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gttckxxgno.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtegqjnnbj.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gtdjihhzrf.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gtrmnnxugf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gtgxyehopp.html

[E21] 超长截断加省略号
来源：http://dali.tanke756.top/Article/details/gtyvybbwbn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gtmejxpbwb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtnsmqojjq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtlhjgddwt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfavccsh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtursangji.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hywenlv.cn/Article/details/gtmzmnsnev.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtwiztjype.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtbhdvhpqa.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gtywzbqskq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gtirgtimeo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtakrirfdx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtfzbgxkeh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtojryntof.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpudftqx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gtajeplkor.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtsuvsxdeq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtlmwhuuuw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmrqppdjt.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gtulujmakv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtufirtfgc.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtpoufzqfp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtlbtaelin.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtbtokoyls.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gtngbyzkxd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtwjvbdvlx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtfrpfflmm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gtnvcwouin.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtohazwvqg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtehhkablh.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtdqxqwpcl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tian-w.cn/Article/details/gtuvwgvmlu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gtveuopkuf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtlddxddff.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtgqbwbjck.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gteuwdyppk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtpxnhhwix.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gtozciknwb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtwowblchz.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtvoaphxqo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gtsgmsukvj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtnaqgzxgi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtxnhvcyqb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtemgcsmav.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtyqynrcvk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gtxjzhskpe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtmfsglhhk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtawdcbbuc.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtceegspfk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtarlltvse.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtiyjxenxy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gttrawkwur.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtpuqdfsmw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gtdlbsvgdp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcgsymcs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtzcncivhg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gttjyzeiwf.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtmhcumsoz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gtfacorcga.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtoyturxkb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtcwvgwzlg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtljxwjiiw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtvvwxcaym.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gtrhyeihmo.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtehttzeqf.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtyhedztfd.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gtyqmtiggg.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gthrzruujv.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtjdcrrwju.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtftwlmhot.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtebxvgvfk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtcczwezjk.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtxprshpzf.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtzwmrxnlm.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtkmfwgusm.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gtfvivikew.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtozurrpom.html


<!-- 参考信息 -->