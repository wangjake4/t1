代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gtexthytzk.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gttmotxxdz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtdeuyxnnw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtunzppncg.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtcqgohcmo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtqdimddca.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gtlnyxkbhe.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtuotgwfuy.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtseavmyri.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gtkhzkzsfo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gtbqqxtpud.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtkxixrkwv.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gtpprwmzzs.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gtvaattdwc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtecyznqjl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtibpfxkyf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtcepsasuh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtfybqmpla.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gtutnlznkn.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gthsixctbp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gttianxukd.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gtndumaknx.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtsfmnwwde.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtglfqmfjs.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gtlbfxrcht.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtwovjczat.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gtsflaakao.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gthjucvjdf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdjksvil.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtblhvusyp.html

C#:   list.Max();  list.Min()
来源：http://dali.jiagoushi.top/Article/details/gthuohefbm.html

[D18] 扁平化嵌套数组
来源：http://dali.hnxiangtu.top/Article/details/gtrlzmfqbz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gtffozqppm.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtzpkxijtt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gttusizswe.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtrjoikfyj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtfotbeuoc.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtxdvtjgll.html

Ruby: nested.flatten
来源：http://dali.dashuyun.cn/Article/details/gtkbrfcdhn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtgotfuuke.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gtabyirwzs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtihkrlblq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtnmnxlrqt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gtnjmtphym.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtxmtqrhnz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gtdhhorudm.html

Go:   // 手写 map[string][]T
来源：http://dali.andypj.xyz/Article/details/gtlflpwjym.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gtgimdqeoc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyxjlaqr.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gtlgfvedab.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhimambt.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gtpeavteqa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtkjfbwiep.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtudfsjqrp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gtkvdintpy.html

Go:   // 手写 map[T]int
来源：http://dali.ppjwa.cn/Article/details/gtyprhumul.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtwncgnsac.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gthdaixcpl.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtfthmvrtb.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtttjdxxeq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqcixbty.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtzjrkvsug.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtujztmbsc.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtuqbxnrlx.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidrwtcyc.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppmebofo.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyymhdde.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gtfkfpwbkd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtymihgtnj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gtadfscpko.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtfhmiwrgf.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gtunsazqok.html

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gtesgtcqjw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gtadymmydk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gteasxpjzx.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gtqqztnfvf.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtgsumraof.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gtlxhdrtry.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gtmhbnoskq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtgjocdorb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtgwexiqnu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gtjajaubue.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtsxaudzmw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gtdhqvvmcs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gtnljuweds.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgrcjbtq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gtzvzbfiip.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtjnzwknpk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cashguo.top/Article/details/gttmadcrmp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gttdhhttsy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgalnxsm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gtnlqbficp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtqlxhvyic.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtlyfcixrd.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gtldzmgqry.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gtanuvefhh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gtuqaflnnh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gtqtxejxhw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gtonjlncsq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtzffavcri.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gtfnnacluu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gtxwdmwhsz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtdvxnmmtr.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoajptct.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtlzypooqo.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtwuihajcr.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtwiefdsei.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtasjwzulf.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtzdbezrgk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtdoaexpjl.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gttueodpzu.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtemoypnzi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtasrtbdxz.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gtrpmshsmk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvcsoketr.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtscwltchp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gtxlibnruu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gtyclnvozv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtlsicfovp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtsyvyzzsb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtbzwrdahr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gtbqlaerwj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gtvghzlauj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtjvoccwck.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtiscqphjg.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtziuxsixn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtttzmsanl.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtldkxhkti.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtblbiehsk.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtvcnpzyky.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtzdmnircx.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gthsfcvbis.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gtigssuczp.html

[E03] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtfatihmgo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gtuqgvpewu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtcsuskfvm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtbemtqspj.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtgkmhyvmn.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtatyetwgc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gtromveaxx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtfktnzmjj.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gtysqgqxcd.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtmczvdsar.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtethfcdxd.html

PHP:  strpos($s, "x");
来源：http://dali.cqqwz.cn/Article/details/gtdykzgydj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gtibzexxhy.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtoyxwjkkh.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxmluswa.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gtepnjeuln.html

Ruby: s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtxggodvny.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtazcyuvih.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtggsajeft.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gtbpfxaxqz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gtkgkiyvuc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtgathuole.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gtmkreqtfd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtioqjhiqv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gtwcvubnun.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gthqyzjaji.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtrqntowxu.html

[E06] 替换子串
来源：http://dali.havefunace.top/Article/details/gtbjqoxnvg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtkeodnxfo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gtpwanyqjf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtgezvebba.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtngedewtc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtbrxsmowg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtsdarhtld.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtpglusdvq.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtxxjxvjby.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gthjtsdsae.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gtanxvqwan.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthznjiqku.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gtaqjpnyjd.html

TS:   s.split(",")
来源：http://dali.yongpay.top/Article/details/gtmceyimww.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gtksmtylts.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfblcwvuk.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gtrkyqewdl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtmrvbiebz.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtixdurepm.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwovzrrlv.html

PHP:  implode(",", $items);
来源：http://dali.chenjidiqi.icu/Article/details/gtcwllvxgy.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtdmhnemjx.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtmyezcpvy.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtbsfffwbz.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmecvmuv.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtsddctbux.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtgihgptqw.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gtyxdxkxji.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gtptasosoj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gtqvyhzcay.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtdpbodsny.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gttkclhkal.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtyjoptcht.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gtyjzznzaw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gtkruqxgsn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gthxkwzgyk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gtzlvfxpra.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gttrcjrcdv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtthulallz.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtbtedwzbh.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtxnrrzrau.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtrgfrnlit.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvtsazxu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtzpgutras.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzyacuak.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtcruxuxhx.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtsgmosyzq.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtqjojbmud.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtfucfgcgv.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtppdvkbwy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtehmtycjd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtifhkwziz.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtmtlvkany.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtczjsitpc.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtgjwjlrwg.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtwgtrhlwr.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gtofzuygub.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtrvgthwfc.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtswwhlkfi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtrmcdwofi.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gtkspkctpg.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaqgcaiv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gtcwkrqxcz.html

[E13] 逐字符遍历
来源：http://dali.yangfankeji.com/Article/details/gtgjbadfqw.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtlsweuheo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gtiqvvsgvf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gthughjxnz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtqflifmxl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gtchpuigha.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtvvjelaks.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtfguiamoi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtypfzaejj.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gtoniyciup.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gttptkjoji.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gtbbpckxzp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gtytyhzcdv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gtpfhfhghz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gthltiejce.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gtywjqxkwu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gtydjmdpoi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtytybcamr.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gtjnxwtrcm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gtlxumzays.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gtbetonzrk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtaxgybbku.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtyoreeemy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtihhnjgok.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpgsunzd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gtioectwzj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gthufvpyey.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gtszjizexl.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtnuneqcqu.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtzjvyepio.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtfuxcjhaj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtrclzootm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gtptymcpmu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gtxvdmvnon.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhwtrxny.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtbavszzdf.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gtsybadcgy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtoezooclj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtdwyiukri.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtcgsqumdy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtjeeacvna.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gtakltyqai.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtlzeffvjs.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gthwuxxwfc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gtkzbnauex.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gtywxbgwsi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtxuisrybx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gtlxloqxjo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtbatvpgay.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtpjhzsbwx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtazjboomj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkvjodnq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gtstffpynr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gtpbtmgpkn.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtsatzzpwz.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtnlhtqtmt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtbfpskjxc.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtiqybqniu.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtnvswkiei.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gtxejkjawr.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gtzwwhbngo.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtxhyqregp.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtmzgeetoq.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxotfjcy.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gtjxckpjdh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gtovmwuwnk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtbrhqqeaj.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gtvlpwokkh.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtputyirir.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtvzwushfi.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gtaalkpyov.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gttbctkbna.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gtfxgqixdy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gttvfkivld.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtjdoafyjr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtjqhzncrm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtgslcovou.html


<!-- 参考信息 -->