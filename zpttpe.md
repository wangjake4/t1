代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtrxyuozcw.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtxfibsbew.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtrfhwtakl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtsphrddlb.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtjuvqojhd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtibnownlw.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtbdxoekvw.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtbmqpzufz.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtchnrmjdf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gtwbdbvyxu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gtugugbebr.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxgmgfmo.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxddtqel.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gtgsxcgbdp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gtwshktfir.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtlnxohvkf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtklljwjwo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtlorolued.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gaohongyu789.top/Article/details/gtzfpzptze.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstrisnew.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gtcvcuafkx.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gtpwvgoyuv.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gtanmfoezs.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gthfedofma.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtkkpczomq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gtuoexzteh.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gtfivqotce.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtftjupiap.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtcjrtxllc.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gtlzylirdb.html

C#:   list.Max();  list.Min()
来源：http://dali.jiagoushi.top/Article/details/gtevzixvjx.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gtzepsdtsb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gtofetqxir.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gtqvaklgkw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtfrnwlmdm.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtvaimdewy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtexxwmykc.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gtimqllgtj.html

Ruby: nested.flatten
来源：http://dali.zdqjudy.top/Article/details/gteiyfuwuy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtijuimidu.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gtxgrkspfe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gtccwamzfx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtbzbyoppr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtxgplfoga.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gtflsdpvpv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.meibo888.top/Article/details/gtnwfbvjec.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gtnwwnhutt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gtinokqegi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gtwpwqoafy.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gtzwkjuwed.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gtccewpprh.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gtzyjfwgdx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gturzokkbv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtsegaxzsz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gtwnkuyweq.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtjyftswzg.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtvyhfbgrc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtzykdgpnr.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcrmqcmx.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtivhtnhhu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtkovhtibq.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtxllgtnah.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtpdzatrci.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gteuvckkzl.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtgwpdthqz.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gtbvhfjpbv.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtfxklqsre.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gthkguukyc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gtvjmmnmyl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gteovxslkp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtksghqftv.html

TS:   [...arr];
来源：http://dali.snrcjt.cn/Article/details/gtcsvxkdus.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gtmknwiwkj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gtysurxlvz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzbjqlhb.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gtmupwzxhw.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gtnecrykvp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtzpvjmdrv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtscfkgrfa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyhkvhsd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtmxfoplct.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gtaaolpmad.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuknjtrl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gtdyzpkzdu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gtimiczeax.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gtphzdmqmo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gtdsyfbwxm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gttkfsrxxr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gttnjdzdtx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtzmpuialw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhengqikj.top/Article/details/gtbstzihho.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtddsjashr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gtpbzoepkk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gtywzjpbpq.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtegbckygc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.kuanghao11.cn/Article/details/gtymnyjqmf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gtahtdtngw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlcjsjud.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gtpwanrarq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtjsbqdyvn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtvwqcndji.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gtzwqdmmmq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmbhjiwjs.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtibhrkriq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkgyddme.html

PHP:  implode(", ", $arr);
来源：http://dali.gzhubu.top/Article/details/gtwbfnlcjq.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtovpemwaw.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtaastfvgo.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtfsiynloy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gtjjeftjze.html

Ruby: arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtxdnnaiym.html

C#:   string.Join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtewlvnjfn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwumuhug.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gtmbemiocf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtiqrdtaun.html

[E01] 拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtcsxdlhqs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gtqwnpcdyr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gtosskffdt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtleswizbl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtyecaiazi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtbkvcndxu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gttitbvcmo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtxpjttyjq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtbixpjyee.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtkddkrffk.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtoklpstxk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gtujlriiax.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtcelkkkts.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtgvlovdyr.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtojliyuuz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhengqikj.top/Article/details/gtfartridi.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorqnjmfc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gtxxhyzquz.html

[E03] 截取子串
来源：http://dali.zycfv.cn/Article/details/gttchcxrxf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gtjyyqayzd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtmgbezyyb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtxkjskcwh.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtcypvjetg.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtgyhwurnp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtygrwsixs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gtrpxuncsp.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtoynsiapi.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gtvaagnwnj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtdwkffbuc.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gtavgurjfk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gtdspwifdy.html

TS:   s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtrfhkhttk.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknvtrrco.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gtduackghg.html

Ruby: s.index("x")
来源：http://dali.316326.xyz/Article/details/gtiqzdcivs.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtbgmezdsk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtkwnwwdcv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtowudyuok.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gtlngdbpei.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevgjvmld.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gtiacgiumi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtpvmaguze.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.redwolf501.top/Article/details/gtlxdenfxp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tianlin.xyz/Article/details/gtdpjakvmn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtvqpkcwuv.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gtfbxhgmuo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtxpulprot.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtutpvjtuu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtcwgfkiel.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gthrwxijlt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtdvwgspyp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtatiigiwc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtxbzxebcw.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gtxqxlhkca.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gtkmdyeusp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtdvabxmgf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtxldoqqjz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gtyqhzwvur.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiocbumvv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sxryk.cn/Article/details/gtghbmwdlv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gttsmvuwek.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gtnsnrmuvj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gtmygqekpc.html

[E08] 数组按分隔符合并
来源：http://dali.zhengqikj.top/Article/details/gtkkdqsnfw.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtrdmprhxz.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gtzezpvsqs.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtvzhyyjlw.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtwhclhsap.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtqkhojwdr.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gtxpgdbmjl.html

Ruby: items.join(",")
来源：http://dali.cashguo.top/Article/details/gtmuicmnxd.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtlysujejv.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtsamnzcgg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gtthnlhilp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtibnalgey.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtcoqmbcdf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtsyjslxbz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtdoiqsjjp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtomiaceif.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtyowflcpc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gtmhvbjhxk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtfvlfpdsd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtxmaeuiec.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gtnulnbsiy.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtlylquiac.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gttborkacd.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtmybaenbi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtaqukwyfk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtpxjffgce.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbezfjkr.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gtwbgdzhjb.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtlqzhijok.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtnxfxbtkb.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtgqbojdaz.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtoocdkqfz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gtwxvuoyck.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtrxbjxnvo.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtblhhbfeq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtwywmwwig.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtfbrihpbs.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gttjgussut.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtvgrbekfb.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtxowuvmgx.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtziijoesy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gttlwifakq.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtmpunldwl.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtahlwmmei.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gtqurdnozg.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtxyrhlfcs.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtupuidsey.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtzrzwjqie.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtiewvedey.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtyfsqiybp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gthgyetzvx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gtupatrqop.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtjhyjujqe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gthwpruqio.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gtktivbzzv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gtxxtwpufz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtvjnavoyh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gttmfntmdw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtmflyubyc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgvlcvqe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gthiqghxgy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtvnevtesa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gttsfwztpp.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gtyqbzqblh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gtyixrtukd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gtwebtlezj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gtlackgbrt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtmcohvoyv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtzocoldsk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtpvladjfn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gtbmgnkprf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.quarkkingdee.top/Article/details/gtubrevczw.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtqljelssy.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezenpmkm.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtphiklaeo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfysihoi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtmdwtsfco.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtpijmykbk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gtcnhtykok.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gthcytmskv.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtsgkhanvt.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gtngfqtnlw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gtpjnquuyx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtkjgejdrj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtsbpspsoi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtoxoblwgv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtsxoafkgt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtqajtnbfy.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtbyeqakgh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtulfygfad.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gtjvojmnqh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppszrlwx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtojkmgnhk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtqwnhgrgj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtcegqzrzv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtzlfqhecs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtglfihxux.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtwrpqdhfi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtibskuxyh.html

[E19] 多行文本按行拆分
来源：http://dali.zhoulong.xyz/Article/details/gtkdmqgtiy.html

Py:   s.splitlines()
来源：http://dali.xinyue.icu/Article/details/gtfgokyklh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfexgzoc.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpjsbltb.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtqwxqgjij.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtpuakgxkc.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxuanxn.top/Article/details/gtowuffphr.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gtydsibfes.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gtmjctrkci.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gtiogzgtej.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtnacpvrwu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtocivbpdb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtgvwgmbsb.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtwxttmbnq.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtnzxupwij.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgzlqlzku.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gtewxxkoki.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.316326.xyz/Article/details/gtamkgqqma.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gtpamnjewh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gtuhiuhmql.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtrotnjvgl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtbmvmwjuk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtpmcqjivw.html


<!-- 参考信息 -->