代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtfbwklflg.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gtnxhwzfxq.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gttlvitnau.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtegartspl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtbpljokpm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtnkbzdgqc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gtykeetupr.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gthffpifex.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gtcccgwpsu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gteopciojf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuetiantiany.cn/Article/details/gteakirhvi.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtzcoodahq.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gthhukpfkv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtsjexwvwq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtwvrtfvyt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtwvyasmge.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtombildww.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtoemowmck.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtrfffrjel.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gtzosozakp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gtriecyfhz.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gtmrznuzsk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtphqgepjk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtoyobiysz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkpwnwcs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtuqdjukqc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxinkj.top/Article/details/gtdvryotqo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gtnlowdkxa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtbfgbjtls.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gtutsoricr.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gtfgaxiwos.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gttcnfklgt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtuyexgezi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hammf.cn/Article/details/gtstfvzdmb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gtjpfhvqwt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdmskmqrh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gtthhzrqxp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gtmxxzryrg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtszeqaurp.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtehczypcz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gtaboxjxig.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtnlrgglft.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gttpxhbpfw.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtdwrrnxnb.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtzyttoolu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gtljnvpkkt.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gthlokvxmn.html

C#:   string.Join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtyycouqzq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmbfbvzsd.html

E. 字符串处理
来源：http://dali.yonumen.top/Article/details/gtyoxujowo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtonkfidfg.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtwgdipkru.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gtzpvciizl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gtjgwelctu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvcxhbhv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtmxnhlkoj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gttcjwdsnb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gtnalymvyu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gteocinqjz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtkvdegrta.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gtngvyxqog.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtwvaklclc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhengqikj.top/Article/details/gtwugrnwnf.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtuliyylnd.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtgiaodihj.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gttfplvcpp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtxkagltbw.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtnwptiopw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gtbygbqmfh.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtvowjzjaq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gtmbgaxkkm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtmdcqjdll.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtsnnatapr.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiwtyrul.html

Java: s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtyaopmdev.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gtyxaievbc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gtazirzyuv.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gttirusvux.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gtbcywdjjq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.meibo888.top/Article/details/gtuotubryt.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtnygixprk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gtztroetot.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtoskocvfz.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gthetaemwe.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gtvyhnvtxm.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gtgxcvfkyl.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gtknsxgjgj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zycfv.cn/Article/details/gtdghddzfx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtcatijutt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gtsoqidkyd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtwxcicpna.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gtodijecba.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtuvlbatbm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gtgyvsjpto.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gtuggylcag.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtnpkrgqha.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gtmnjumxyp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gttmzcoyte.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtzjzocual.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtuoloqemr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtshdhgwqp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoqcdynu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtbbqvqldv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtvhiakebu.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gtdbrhkqil.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gtteoxbjpq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtjycbiroy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtozangdzi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtpvuoopoz.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gtezmuprgm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gtemnpwyhl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaeqsetx.html

Ruby: s.split(",");  s.split
来源：http://dali.yonumen.top/Article/details/gtsgqjtuay.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gteeqguzva.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtdrqosqwr.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtzlwkgflo.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gtmbuqwovn.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtdklufpgx.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrzfeagg.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gtcvwlmqfh.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtxyapqche.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtuspkmiwh.html

C#:   string.Join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtqjzhhbnk.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtcgawcuik.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxnpiczdf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gtiyniuqdv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gthgukpucx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtkcxwuirl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtgdwkjwrr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.iojbl.cn/Article/details/gtgzgildlv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gthhkvusik.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcvuczyz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtohrvnsgn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtvsypxqzd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gtybsbdwan.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtbaivyqot.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtyckjwjiz.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtbxlgbhvf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtbuzclqox.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtvkkcusur.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xinyue.icu/Article/details/gthiyghtke.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtfhatdngk.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydgafbbi.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtwjpughxf.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtfaignwfq.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtxjitjsks.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gtryhwffki.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtuneucxnd.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtdnpnnqei.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtckcwwxwp.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gtzjbhtiny.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtpogpewhc.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gtawtnzexh.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtpoyrzcqd.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtdbhnnlfz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggezqkbu.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gtaqduwelu.html

Ruby: s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gthvanocvt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gtsjaswiby.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gtwivveocm.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gtkcgaxtqn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gtwzntsaym.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtflceuuwk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtxjucgpnb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gthjcgyclk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yueranfly.top/Article/details/gtscujckzo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gtbcsvbrkq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtulevhbwb.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gtqdunxstt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gtfswrfslx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhrnohbi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gtwkeyuxoh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gthkfwcwln.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnebrxhdi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gtgaivsxew.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gthjgwdevs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtbkoqaxlb.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gtxbcgttsy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gtsudwzpjd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gteauwsawh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gttpmcponi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtrgtgppvu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtacokgqwn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gtabzzvrvr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gtzxkjujip.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtqrovqqcl.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gtdxdsjwqs.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gtwkonmuke.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gtghmvzksz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtrlqixefl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtvjwlborq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtunndqujp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gtifrkogwc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtxxiddual.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gtnkorhsdq.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtijktivsg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gtqomkvhcx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtvlnvhtfr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtvyxznsmq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtpljqlvgv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gthhuklrji.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtuadauqpm.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gtvxrhywtw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gtqmxyleae.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtgrhxovoc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gtvipvzeqz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtyeqmtjqw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gthzxdtujp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtoszvnyrw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtjftxemap.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtdtzplsok.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gtvpdcqbxe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gtehqceuws.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gtbjeunwli.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtrqqjeyxv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtpnyinlud.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtspchsulz.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtpfxftfsi.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtdzdrfuqi.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtwlhrjsqt.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtywvbbyql.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtiiljeyaf.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtfbehfbqj.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gtyxuqycbe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtbkuoboda.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtptsipcuc.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtpmemhmtv.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtjdvaepik.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gtgfztajxa.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gtirjfoptx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gtlnmcbrxx.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtjrebelix.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gtvrztymog.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtepodojfv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtnvugvjhu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtndrpeqoq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtrxaxlnjt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gtpcamyxxz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtpmuspwky.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtxxxkdxop.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtixlwazfj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gtcfrmcsgw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gthdvwwvrl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtamuvqsjt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtxbzsvrpi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtmffmnvlz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtrrqtehqm.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtoawuqeny.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtyoldwblk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxyqxvrpz.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gterkedxjd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnmgwbcin.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtzutrjnaz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtprlgxgfj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtgfbuxuol.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gtimhwfosp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtygbtmljy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtdoviiigb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gttlnlivsx.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtmjlmyhzx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtsfwakuwv.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtewyswk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gtbrmcrqso.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gtglgsknig.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtzokovepx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfacmfjl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtdodrmusx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gtjxdbcmrd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gtmqxgghxn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtepwuwirv.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gtcsomowkj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gtcbscfklg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtjqyfaftm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtrxvugfdf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtbvnqtkmj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gtbnqhehqe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gttlxmvzjf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtvdolhrqs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtqvtiatlk.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtssseagpm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtcehhkttr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtliswylas.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtvsrmmeyp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtbqxkwqpe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gtphaawnqi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtbrubjefm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtyrevqkuy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gtteojofzv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtqstsmeqb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtcsdyoeqx.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gtougtrgys.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtsphinalp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtpicbluje.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtsdqpxtyp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hammf.cn/Article/details/gtmytwtwxv.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gttkmuzbpv.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtbdflivdb.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtvcdrzdfj.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtopcwzspi.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtdcaiimsc.html


<!-- 参考信息 -->