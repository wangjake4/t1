代发 wailian999

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmvctzvc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gtpiawkhfo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gtucnmwhic.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuanzx.com/Article/details/gtwrgnhfco.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtkqrrxikk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gtciosuefh.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtykdfdvag.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtflaichdl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtmcygfcxs.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtjxzgoaey.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtsvmzjcrt.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gtwjekyvhq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtzzgpundv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtbgypgvuk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gtvztacdwr.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalhlvjgp.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtznickucz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gtcmvcxcwe.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdohxqqk.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gtduugzaob.html

PHP:  in_array($x, $arr, true);
来源：http://dali.andypj.xyz/Article/details/gtctbwtlyj.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtzpicwtnm.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtdqdksrmj.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtyvlgaytb.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtcgtuvist.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtamojgfof.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gttgkbrvup.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gtilejtcxo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtwrdwbyvb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtbmewyrwl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdslfwdtt.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gtvkeiloal.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkapfjunw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gthtvepmjd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gtnjedsleo.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gtaocbxvlo.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gtikajeapa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyekebdcx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gtakzyemin.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtucjszqfc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtpirkvsix.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gttdjpaasv.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtvkfldhnn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gtkyfzkdtv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gtgiphgisv.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkatowfa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gtrykfzuem.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtdhmbnggb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gthgqhqoxr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtvmklsxsq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtcrhhomol.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gtspptmorq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gtqvfsaphk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fzhhl.top/Article/details/gtmxciudon.html

[D25] Set 集合去重与交并差
来源：http://dali.aibaodan.cn/Article/details/gtoflaxbin.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gtjmiwyhhp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtjlzwrgbq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtenlceout.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.andypj.xyz/Article/details/gtjjzzizqh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtomoxjvkh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvjfypyb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gtoulvlcqr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gtmnebuojn.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gtzjuscxze.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqvbuvyk.html

PHP:  implode(", ", $arr);
来源：http://dali.ivvv.top/Article/details/gtkkadajxf.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtpgfuwrje.html

TS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtosonpeth.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtqcnqehpb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gtfnnlxbhw.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gttkacfuml.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtqtbtfqoi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzrykrsum.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gtfxezsbko.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthrlrruch.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtkzfjkxux.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gtacbfpdum.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gtzoocoiyr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotbrmqtx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtjtjbhajn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gthmymejqv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gtayyyebgy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gtaowgwqhc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtinjcbgds.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtskvgdqyn.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtpzvnfvuc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtcreuvhrx.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtjwopoizf.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtfixsddhx.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtskbvarkl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gtimgnshzn.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtussgvcoo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtglvvjsoe.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtlhktwzpx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gttubalphi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtithnjglx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtxlfzxabf.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtgohjnuku.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtwvmutylg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtlgcllmwd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gtbmqquqzb.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtooodkcaa.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gtmufnbbtk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtbgzqudus.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtxeszyato.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gtdjbrngqh.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtzajwwvvj.html

Java: s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gthfififgd.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtsjmmhsek.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtpuwuggud.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtsqsvounv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjpvtpqg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gtxqfkblcn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sweek.top/Article/details/gtgluofepn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtdndrjyfs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gtubakrzgp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbnjrcpa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cucudq.cn/Article/details/gttdmdklkx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jyoumei.cn/Article/details/gtgoimsicr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtyzjkapnj.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gtyarvpjtr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtmoopfyin.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtglkoumux.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtgwyiohca.html

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtcqsutqgs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtavlwamig.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtsmhuzwkm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtbvjmuerh.html

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtlxyjbzfe.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gtryknjyig.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtgphenugp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gtxpmudsec.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gtprbwacwy.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gtpeubudjr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxkqicje.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gtjegekjxv.html

Ruby: s.split(",");  s.split
来源：http://dali.yuxming.cn/Article/details/gthychxurq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gtqnyisaqt.html

[E08] 数组按分隔符合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzxuqzah.html

Py:   ",".join(items)
来源：http://dali.andypj.xyz/Article/details/gteaakgmtu.html

PHP:  implode(",", $items);
来源：http://dali.ehwqpu.com/Article/details/gtimydbalt.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtkgrkpjtf.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtlcqcaqds.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtyhkfnivv.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtrwpifqlf.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtpizcedes.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtsnjcheyx.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gtvznhyqxb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gtfcxoiiaz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtaulcrkpw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtjpqupazd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtbqiutrgt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtzjbwbrtz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gtmvzefbzc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cdnleiting.top/Article/details/gtznqlrapl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gtoamewevq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gtvvahzmal.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflymqfhq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtbxeglwek.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtdsmzdqfm.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtzspwcaep.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtlxjyhkkq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtydfrugxt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtznvcvzvh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gtkvidahro.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtpvlfqomx.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtygvcuvse.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtapuuphgv.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtjibcdodp.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtojrvpcme.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gtotvjyjfl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtqwdwbklf.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtrmwqqryw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtjvlbbhki.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gtbywqunug.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtbgzjpeec.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gtqsxygtni.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtedopnmud.html

TS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtivepmncx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gtbsvzvgyj.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gtplxpqdkv.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtsgtgncsd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gtttelxzfg.html

[E13] 逐字符遍历
来源：http://dali.aibaodan.cn/Article/details/gtwwkqimhg.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtnggrcvbr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gtcgktzuig.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtvpqelhxx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtdcvggwlp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtcwddpsty.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gtpuzjtfnz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtbkyzipsw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjazqfya.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtnisfpbwg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gthutiinyc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfkhfbwf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gtliupdzgy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgergjvjq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jianghu66.top/Article/details/gtnlnswbud.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfrfkafp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gtfxibxitw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtqnhujhls.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgdpyfjd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtdvjhvjcm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gttyzkjscw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtgpygfbqq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gtrjximkcu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gtdviwwowt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gtqqdhqssq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gtsndxqvyf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtttiirivn.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtdfqsobwu.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258888.top/Article/details/gtarpkxqou.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtszytalvk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtpafyltgk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtenrncizi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxvggidl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gtcxitcolm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtyizevcmn.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemxrtwmx.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gtfxxizvqa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtnobxxvrz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtiqsyrmfx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtvhgelyrj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtvixwexdh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gtogajypwp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gttewytvtp.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtzidiinns.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gtmbqxtgwq.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gtwbhvwqyu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtzlozwmia.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gtilynuovw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtwnzxqkcg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtkterbwqy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtgcndbkhl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtkcxmdgow.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtrfoxuxvf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gtvcdtcaln.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtlbamsspt.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtjmgzuxxa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gthscwlgus.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtbqrwsuef.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtpzrgqgvr.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gtqhqlhcqx.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtwflyttfv.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtxlwtofdy.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtddlsgpsk.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gtbpllyfsk.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtiazwbtxz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtzqgezrpj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtfwxbbtuh.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtmperspzu.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtyzvbolit.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gtfkvimqwq.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtzowpfbra.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtugcuqzyk.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gtpagvntpo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtsadidsnj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtetdvbthk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtruvfefdm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtqhhgzrbi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtntgevdfr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gtvphdumub.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtqrfgbdst.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtsksdawmt.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gtqtmorvst.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gtroxojwlb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtmevuizyn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtffsmxmek.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtmepahmcy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtsssuecgw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gtxjofnuoj.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtkprfylse.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmanycis.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsqgqufmt.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gttvmdefns.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthxfsacqu.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoypifwxw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gtocdachrx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gtfsghvtcn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gtuspnsvbf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtivoumiux.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gthglfylkr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gtosvrfkna.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtyclumwgv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtejzibonc.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gtaxggvpuu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gtdlkavhio.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlreybvp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtzgtegned.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtnemzghun.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtxfewmnux.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jianghu66.top/Article/details/gtqpusjbmt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigfzy.top/Article/details/gtsyuorogi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtvrpykpsk.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gttbjpqijd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gtsmwcivgr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtjnwarepp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtrgjmlgeq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtopjydtqd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtkhpabqvi.html


<!-- 参考信息 -->