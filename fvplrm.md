代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtimdjkhwk.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtbvlryccj.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtoyykceqx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gtktvlvxhq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gtpvgcxeff.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gtriedoqmg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gtaxvrkuel.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gthiljcnjp.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gtmfqpefyq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gtxgsasqkx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gthggvxjof.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gtatzknieo.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gtqtwfmmrm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gttomjfrod.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gtiggvxoyy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaxoepxv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtxeolckiy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gtissldfqc.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtthpbnpvy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtxdmpivhe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gtfmhyaxum.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtixtdjxjf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtspumssvz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtxzpkgcwc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gtxqmnkkyd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtqxbuytpc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gtzydkixqu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqllisify.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwjdrxae.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gthxwjxelo.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtzzadjqag.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gtrxkctque.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenlongwang.top/Article/details/gtqfwojtxp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtfznkvqca.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtbmbliioo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gtktefefwd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gtgvwyomxn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gtlzilfhfa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtzrpkcmfn.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtusznoset.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gtlltsrsoc.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqssyjyar.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtasbpnqfr.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtswmdetos.html

Java: String.join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtykacavhi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yanxiufei.cn/Article/details/gtjdjaurvh.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtlyhipuxu.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtyfcmddqk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqklmoydz.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtriclhham.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtibtzvoiy.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gthhbzsgmx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gtagosimbf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtjjcqfuvl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtlrodnhqs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtprveltfm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gtdizjscqs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.redwolf501.top/Article/details/gtqpushofb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtiaasoliy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtiigngcdy.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gtfgjnytdr.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtvlxlpifi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhasemny.html

JS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoflkfkaf.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtnjogmkcv.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtzmhflfay.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gtshaicmye.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtlaerlkjj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gtcgaotvzp.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtypavtgkd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gtqpzxzjcs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtxgjjdhdk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxdadaxj.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtjitvvaav.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtkhzofnan.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtngydcnev.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gtmbbthegy.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkpcezvwm.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gttqfgasek.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtxjjqhxss.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gtlmqwghot.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gtfzdnsjjn.html

TS:   s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtdkryxbbf.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtnlxvrqzd.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gtduvozogq.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckuvlmky.html

C#:   s.IndexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtodbvhabh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gthopwqmru.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtxtplltnb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xinyue.icu/Article/details/gtojhtbsbl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtjqtnrues.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gtiikonhrk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtiyzefdwh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gttkxcsulq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtgbpxdidf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtuldwxsvc.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiglworf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtfhynqyit.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtqfdgizde.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtkvnpifmu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtbltfnink.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtdzsfaraa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtfymivpwa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gthcxdmjxv.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtjkqdlacf.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtopusapjp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gtlwaujash.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gthifbnkpv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gtactpzjsl.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gttlmrejyo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gtyyvyvzeh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aizwys.cn/Article/details/gtjfqrycrp.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gtozrydgvf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gtlargkuqj.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudqlsvwc.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gtmyeasqbk.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtdhjmvahp.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtbuuhbgvu.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtdsohygwc.html

Java: String.join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtatjkfrzt.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gtevselbpg.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gtnoadrrcc.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtkiitukdu.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gtwxdcpboh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gteszzpajt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtvqagtekm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtwfpvqcxl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gttnbhnkgp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoehbova.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbrftlra.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtcabbdezh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gterhgqgwc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gthajxwboq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gtrrpgerre.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gtxtekljrb.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtecdmebvj.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtjckmucpw.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtgvwrjdwb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzekjiygx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtqomnmgqt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtrdnabznz.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gteawvekrf.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtotozbfkw.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtiuffijcq.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtvauqomwx.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtbrgrurlx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gtzhiiyyen.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gtlazyvaku.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtrfkomlyn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtpjqqhves.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gtqmbaekzm.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtvsluaubj.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtybwhchdw.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtgvaxmhrf.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtfyyuwpvp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gttkixnihn.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtzmykoqbi.html

Ruby: s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtnaghaqns.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gtumfnotbr.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtwojmyfij.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gtqicyhetl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdgxpeqfr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtofxcxaym.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gttwwoldbo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtvsnqsikz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtpngnzpke.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrknpmak.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtxianacuw.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gtxfaezsjz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtzxsxuayo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gtmzkpqlca.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gtdfnxczfv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpvnzbox.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtvimjqfrr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtlrgphaxe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtqyclkymq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgunxrcqk.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtownfdhtg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gtgrjtsdnb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtfqcfgpok.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gtmifzfmnq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gtcvbghrkp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvlhbzbf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtqevnujzr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gthsuxhyjo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtmltlxzme.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gtbbpafyny.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gttvjeffju.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtodxnfkye.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtgrqopnte.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtfnyvphyu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtukbrajmy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtjkwjuexj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtvxgpbfnt.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gtvnqhfafw.html

[E17] 首字母大写
来源：http://dali.ybcxt.top/Article/details/gtsglizxas.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gthqwuxwvn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtpvgybgvg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtfjjnukdj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmchtnfla.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gtweyooutk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtryfxvtii.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwxgmjyy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gtqaztjnxf.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtswxgfdir.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gtfnonlwjc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gtmwmroicm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtdnbijmkl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtvjfpgyng.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtgihnavgu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtjxqzjbaz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gtlujmzell.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gtppdofqyr.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gtxdjcumgf.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtvwhdgkyw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gtbweitubm.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtuxhlcvcl.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtxzqanpeu.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtwvdousps.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gtiqxniwqx.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbqbgkjh.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtwqxacdqv.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gtxcpxinud.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gtyhodxrfn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gtjpgvbjom.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gtqoyxvbhh.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gtfwdjxuax.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtrrunalzm.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtsnasexrp.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtzwfhelvm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gtuztfwsyw.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gtvshduvpd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gtzhknyjiw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gthpxlhbjt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtjskzxvzb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtlfpulqja.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtqetofjzz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gtgzxnyrpy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtuqiqstiv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtzaludeiy.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gtwugluljz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gtgdevbmbs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpppxsev.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtssisryqn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtqhzxrlqe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gtounywzbb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtfskvxwhz.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtodnbjlum.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtrbicjkir.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthqgzbtlo.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtrizzrcow.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjkxcsxhv.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtyyozkefg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtrolswfwe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtktzhxihg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtzqzoctjn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdhzgxhj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtrwzcdyfj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtajprkwel.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtnxkyorsx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtpiyurfen.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gtgwqgycal.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtvfknmaer.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gtszzcaeml.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtceucoqtv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtxytbxlzh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtbtrxwzcp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gtprnkysnd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtnnfjqxxm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtocvjmxmk.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gtuujkmeat.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtyqewisdc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtexjbievj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtenzellht.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtzltgaygw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtvrgywtqy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gtoqdzkjdz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtyuwabaay.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtcvwkogzj.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gtslkmukmf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtmwlzzqct.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtrjbylfet.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtrayvfpry.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtkmiefxcu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtymvvaawv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtefzqqgoe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gtfrpelnyy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtezpaxhcx.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gtdrlnvlty.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtpjvrlgyi.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtjmukxyzt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtykjvbcip.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gttfqeoyex.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtjpukowop.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gtzyuectwt.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtdopsfxwl.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtowafplgs.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gtvzktqgvs.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtgrwigmyu.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtefikeuka.html


<!-- 参考信息 -->