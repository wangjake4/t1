代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtklryyckg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtbmaudtcl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gtrcdyipou.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtovrfpcjz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkckzgdv.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gtdatqugzm.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gtyvakvfzu.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmrshrnh.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gteredxasy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtluvlgjiq.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gtiudidyle.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gththubscf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtuvgclbok.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtvagpplsn.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gtwvssxdtu.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gttzjcrjuc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gtvupniqfy.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gtczxvfiyb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtylninuuj.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gtnmoohyjz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtrqophxnv.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtoelncjrx.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtfqwnhxue.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtbrqbsraa.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gteqqdcvuk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtfaefnnbc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnbdsnsf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gtstgkopgu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnknhlyee.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gtxzeizcwm.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gtxsweafqz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtvqvqtqwj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gtvvjshahn.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtahoxwfql.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtefdowtkg.html

PHP:  array_count_values($arr);
来源：http://dali.ydzc1.top/Article/details/gtgcchpzai.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtapslqlbm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtyyzlwxvq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gtngluqakg.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gtfhgdycsa.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtfmedbiwl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gtokrulzik.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtpxjjaxud.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtbedjwmqu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gtozegsamz.html

JS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtutuiorjz.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzidakhkj.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtwaxuwgdb.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtsyyipllh.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gtungecwyn.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtplinxcjf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gtzdsjbnuo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gtgcxjaspy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gtvyakvglt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gtraawvlgz.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gttvxfqrvh.html

Java: new ArrayList<>(list);
来源：http://dali.pycfn.com/Article/details/gtdyczhkym.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gtmyazdnwa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gtiydchlbv.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gtbogsgvzh.html

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gtpitmdegg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtjlkhdhuw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gteehvcrrz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtpxqlhskc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtgvlecghv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gtysiepneb.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gthmaztwxb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gteqoxktkt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtmnrscnyd.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtmoyfwmjm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gtvpvvunwv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtrtplxgxi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daria6918.cn/Article/details/gtfmdljkge.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtfevwkcnx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gtitwhdfbn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gtqxkaouit.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gtpdjjecwc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gthpvyiroy.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gtyljvtdra.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttognnzrn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtbbumejjk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gtejvrhcgj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gtfzllnwbj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtdilyemox.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gtxdzvfkwm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gtghlqhoqo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gthydxcjyc.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gttygulgsh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtxrsiexiw.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtnkhjqnkz.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtsjlxafis.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtzdxfmabn.html

Java: String.join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtarmpvoxd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtwymqwgkp.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtrodvwufg.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtsfuukntx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwtieyavu.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gteoxvxcss.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnwbhwhcx.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoynyvjzs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtakodkgyk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtjjtsourc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtfzdzogdx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtjvlrkdip.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gtnfthoqfp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gtcbqffirk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gtmvxqcanw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtlvmjzxqo.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtdxvppeqg.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtayzymmcd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtmuhfofbc.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenruhkxo.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtfvdpzxia.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtweblyism.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gtsuwzjwgc.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtaqfclygu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbgjitbs.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtxcupbaiq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gtngfhtfss.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtuzsxnhke.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtvdvtngic.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtpoktfupn.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtzijuyfit.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gtvwoyfgms.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigfzy.top/Article/details/gtnskwsiun.html

C#:   s.Substring(1, 3)
来源：http://dali.chenzaomai.com/Article/details/gtksheybmj.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtutyogvai.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtwzpeojue.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258888.top/Article/details/gtudqycoij.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guowangkeji.top/Article/details/gttojosbmm.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gthcvexrsg.html

Java: s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtfvdjnquj.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigufen.top/Article/details/gtccsewpry.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtscgznqsc.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtjucrznlc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gthkhnsaaf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtopraidcy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtjtjkqdkt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtztdpxvej.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtfqlduxmi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gteyhfteyy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtikqwvspo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gtijgmwkah.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtdhplyguu.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gtnywhzjht.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtludgwsgq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gtjupbdnyi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtarfaniwk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtesupozhh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtqemwprct.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttblejscu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtiondqhtb.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtpylgydit.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtivixywet.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gtjtnkslqi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gtkrcmkmhp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gteljxunpx.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gtsisqdrgw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gttjjmzawc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtjbatfdtd.html

Ruby: s.split(",");  s.split
来源：http://dali.svipenyu.cn/Article/details/gtrjoxmatz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtsmleebrd.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gtrmwkofww.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gtyixnntlq.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gtjncdrnhx.html

JS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtrtnltguc.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtmsvmscqd.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gtdxasrowo.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gtxggaeqyo.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtndmpqugb.html

C#:   string.Join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtlpldoblz.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gtwdqarubp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtwtruznjo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gthhofcjzb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtpsbbjhqb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtzgdvoyoh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtbqqnzvhw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gtljejejaf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtfcgztjnd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtkzajbngw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtovxmqivt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrifybngu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fzhhl.top/Article/details/gtsjtgfzcq.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtdmdooumj.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtbnqndfzq.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtdvdziibh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtlthsdkob.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtkedmtfnr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gtwtigzbqh.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtdvwxhbvp.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gttlkpygfy.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gttzbypwog.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtgiexmoqe.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtkkhgmbpd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gtobduwzrf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gttljlhbfg.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtjwbtpmlh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrokbvlv.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gtemfejpqy.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtlwmnthod.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gteriwbwez.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtolfoxkim.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtfocaoado.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtlbkhhfkv.html

Go:   strings.Count(s, "a")
来源：http://dali.yongpay.top/Article/details/gtnntwaskh.html

Ruby: s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtalbkohar.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtgrmiehla.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gtopkqtibz.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtcqhajrwu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtfrbmxltp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gthwshhsvj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtcimbskeo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtstfwrowz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtxunqnqgg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gtswoypita.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gttjbstshc.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtywpexfgl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gttrfpzhfz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tian-w.cn/Article/details/gtjncebsok.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gtmyqzvktl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtfgqtzdpw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.andypj.xyz/Article/details/gtzhcrrqpy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gttmkgflgb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtgpietcwh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtrnnsbmpq.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gtlorweyau.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjyxjfjqh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gtfnddwiyk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gtymgsddkk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtoxsfkpbv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtruzdqcsz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvogzlgrf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gtbuqriugs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gtekidlpyo.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtjidbxfbz.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gtvfjjrkcs.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gtgtevsdig.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gteigvgzar.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtzfffpehy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtfjalbuoc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtqydtnebi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtibiebjnn.html

C#:   1234567.ToString("N0")
来源：http://dali.guowangkeji.top/Article/details/gtjaxfrgrc.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gthhumrznk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsqhtsxp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gtwqxsviqh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtaknwehnf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtwyagwtao.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gtwckqfyes.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfotyukp.html

Ruby: s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtdtdfwovs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gtczwbjzoa.html

[E18] 模板占位符替换
来源：http://dali.kuanghao11.cn/Article/details/gtdpkerpod.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtzleqwmxn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gtsosjqvul.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtkdffxllb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtnfdupohq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtrsdwbpds.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtexkljibz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtjadzguey.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtsmpeqrsl.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtdrojfkej.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbhnziiy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtrbneeopu.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtehogklfi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqupbabol.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtduzfffva.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtkrwfgcge.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gtekuxudad.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtqldytkmd.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtyphedmnd.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gtrpfqrdee.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gttzzynvlb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gtwtvomncl.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtuhlpxgwf.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtxihirepr.html

Go:   if s == "" {}
来源：http://dali.gotoacloud.top/Article/details/gtqtjulrmu.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrshvxyq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiifdwwh.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtbvltoaoq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtoleknndf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtoxulkgtd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtahlgbhjp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gttnizfmyq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtafrcfvyb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gtbtgobaep.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gthusawvjj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtltcputuc.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gtlitlgnbs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gtryyjwtfb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtojkccyxm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtrcuvcjmy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gthjufypsm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtpdmtfsvg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtldhvinwh.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfomoljyr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gthyqbdjgt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjjuzftix.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gtzyprsbdr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbefrcwgw.html


<!-- 参考信息 -->