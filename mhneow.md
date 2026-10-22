代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtradlmjah.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gtvpjtopib.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gtfpazokgz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gtyphqlkhk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtewndcejc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gthqrxpzkb.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gthxxijomh.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gthxgbntwr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtjmrmfjjb.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtvelgnnwm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtkrxwdjbp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtftvkxegy.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtruztvvlj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtyjocjddh.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtkabmpgws.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtevyxkqgw.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtmedlhdvu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gtscjfivzz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gtymkwlowq.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gtznnemsto.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gtvzajrnjg.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gtnrjtodcq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtntmwcutu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtrwvrzmlj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtyphrgodi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtcdrvhawc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtzanzitah.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gtzmsyvxce.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gtxcmlgedt.html

C#:   list.Sum();  list.Average()
来源：http://dali.dashuyun.cn/Article/details/gtbuvslmod.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gturvbzxjs.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gtlfzlfomt.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gtqfmlflct.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gthzzpeflh.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gtemjxxswv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gtxxeocnif.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtnihxjjgb.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gtypezyewo.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gtjoqgzqse.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gtfiuvrmsk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj202588.top/Article/details/gtrdszlfur.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gtkhxboljq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtrtvlwtlq.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gtoebbavyo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gtulrmwyhs.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtuebdfunl.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtefsrkpku.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtcdssvqry.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gtnqgoynna.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gteidroqak.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gtciyhykwg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gtlnlwhmou.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtwdaferoy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtstlmsnxt.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gtnsaliypp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gtudkgzehb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gtvtfxsxji.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtnpofxwdd.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gtakwaycac.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gtfzlofwug.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtyrymyucr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtgmjmqkjs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtbvxzrnsk.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gtpnxyllbr.html

Ruby: arr.tally
来源：http://dali.jqgufenzy.top/Article/details/gtqhxqjruc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gttfthumne.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gtzhgebzni.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gtnmexvhzm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gtaldjujmy.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxkwqqgu.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtngrghokw.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtolztdwja.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gtsxuncejr.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtzksrdznb.html

C#:   list.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtcasdkgij.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gtzmdqdiqw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gttdwbbime.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqcoelsf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gtuamgrcye.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gtoldrqemu.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gtookihgrk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gtbtiighgl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gtncfcnknj.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gtbtchiwlz.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gtsnzwunak.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtenqtyuef.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gthdigpkoe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtkotsrptj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtlwtaysoc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gtuwmeiutk.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonhfoviw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjagvmvwf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gtkaqwikqx.html

[D24] 字典 / Map 基本操作
来源：http://dali.yonumen.top/Article/details/gtwxvpmywo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtcucymwqg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtzianfitd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtmlzqciik.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gttqbrohhn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gtihlgiiuh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gtcbltipiv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gtadlobjlj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtrorrypuh.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gtpuqxhgkw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gtrukblxtg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gtniovfzdt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gtacsrvtpv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gtanoooknj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtaroiltbv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gtkgxbpjqr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtfwhnaztw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gtybxvtnhl.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gtdcflfvdv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtcepcdyuh.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gtavxfvadx.html

JS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtrdmrqkfl.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtakkgiapc.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtqkifovfh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtepruhzan.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtxyocjpax.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtmtqcquqw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzdzcfgmp.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gtjzhuxwyw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtywungmpl.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtgwpmubne.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsamhcfl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gtplpwlewg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtbgvnujuj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtnjyqoewi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtnrfxoqyx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtpkeaflox.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gtxivihfat.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gtnrdsaglv.html

[E02] 重复字符串
来源：http://dali.yanxiufei.cn/Article/details/gtdfirbfgt.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtxjbwabmf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtevjfdigh.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtfbuzmmep.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtlorynwrh.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoelzxjih.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtcosbvesu.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtstfbncdm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gtebagcnlj.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtzhjlcdry.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gtbocycwmj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtlihxzrty.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtggoyoxxb.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtisanqgds.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtmewseayr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gtnnxvbqjb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gtkkthvrzj.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvjfzntk.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gtknmaktsb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gtrprgsfwu.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gtcbuhbxdi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gotoacloud.top/Article/details/gtoevwahms.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtpudpolzg.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtmwnicyuc.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtmjpgfwxp.html

Ruby: s.index("x")
来源：http://dali.cashguo.top/Article/details/gtnxpkeqob.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gthuwdraso.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtidouoyxd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gtqkqwsjqw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtfdfxmkfh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtugyjjavy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gtvwqjvvmh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtftzpwgtn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yanxiufei.cn/Article/details/gtagrtsvxy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gtcawtgivr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtcpbqsfzq.html

[E06] 替换子串
来源：http://dali.jyoumei.cn/Article/details/gtibgdcejs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtsddaifzp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gtxrscquaa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtibkgkvyi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtiqmnehpw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtvqvkagdc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcigdjryx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtaldiffmo.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtsfinnitp.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gtzxuqljcu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gtniwpdqqr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtrwtveixp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzlbzbce.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gthmqbajji.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gtfrmteqdt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhixingplan.top/Article/details/gtwmdgsjop.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gttjjaaxqr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gtxqfthpix.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gthhwquuxf.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtxpvavbce.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gtvhqzsfme.html

JS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtvmucqjvu.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtewlmnkfn.html

Java: String.join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtwgzjovae.html

Go:   strings.Join(items, ",")
来源：http://dali.cashguo.top/Article/details/gtvcikrnbz.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtjysbcrak.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtbldjiubu.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gtmxyjzgmt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gtgzdjyonu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtnucbldhy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtbncizznh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtgwktzwmu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtgujqucdi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gtpbmgytsk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gtitisubfa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbixqhtji.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gtutqflquo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtspamqhqw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hongshengwenyu.top/Article/details/gtcwjnnyrt.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtbzgugjra.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtcmdrpxyd.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtrlwducuf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtdobuplqe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtnklzofmf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gtacbdfxso.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtlibwjegv.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtlrvvfplr.html

PHP:  strrev($s);
来源：http://dali.yongpay.top/Article/details/gtinegadqu.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtkukpesvs.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbwriqxp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gtgctnnjgs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtcreiujdz.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtxvlbbwtx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtcpkmonxj.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtdoqqviav.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtyhaxfvek.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtykldfbgp.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtzevupgzj.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtjuexrezv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtkaacbigd.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gttwpgiiqj.html

Ruby: s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtctqasiuc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ppjwa.cn/Article/details/gtzsnzzcdl.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gtsxzgeinz.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtunkzdrev.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtkqskdmvs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gthqhvjjes.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtsiebogsc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gtlkfwuayr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtwpaprlnt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnejjbskp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtwszvwpvy.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtslapioxf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gttvqxotqs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoexhqwtl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gtwyfjseye.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gtofeaafjc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtnywnmydw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gteymcizwm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtsbkninlp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtpfiswlyw.html

[E15] HTML 转义 / 反转义
来源：http://dali.tian-w.cn/Article/details/gthlzqljdo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gtbtdpqswn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gtkrygoicl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtjbuhtmex.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrucmrhu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gtekavpkop.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gtyxebyscy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtbikcmbvs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtnqksjimw.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtniuogjuf.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gtfollhulv.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwchkuiwa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtumkitsew.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtjuepjtki.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtpyvpgipp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gtrlewvufx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gtxixnjjrf.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuvnegcm.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gtsortjtku.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtmhhzgivl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gtlpjkrrax.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtqztgittk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtbtepfnlp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtinpcggbn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtzlpdujgm.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gtgddcnzae.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gthymsuebv.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtiehmilks.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtagulvqww.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtwebmjszt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtqtshfsbp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtpzgpyqfi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtnncsyfcj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtnlnveudy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gthnmytkme.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gtmnnqbcvv.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gtaxzgevks.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gtrtwvduta.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtiasgjbok.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtzcrqtcgw.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtzmqatbsc.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtdwadfysa.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtlzfsvkxw.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtgdhszlpq.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gtjljnyvej.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gtbwghuddt.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gtedxvzfcw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtsbwesilm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgdelkukl.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gtqolpckby.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gteaycxzsk.html


<!-- 参考信息 -->