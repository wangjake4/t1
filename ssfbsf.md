代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtnaluacym.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gtpwqekabo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtecftpser.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvnefpbd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtwgfjicfm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujyjnoad.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtjvftcmys.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gtmrdlweoc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtvhzycjmv.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gtyvzrnbgb.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gtlfqmfpxn.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtnyrhgfia.html

PHP:  max($arr);  min($arr);
来源：http://dali.svipenyu.cn/Article/details/gtmfazakkf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtmzcdsbvx.html

TS:   Math.max(...arr);
来源：http://dali.sxryk.cn/Article/details/gtevhlakqf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gthrqpyaos.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtjjdhlbfu.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtztsqdbml.html

C#:   list.Max();  list.Min()
来源：http://dali.cashguo.top/Article/details/gtltiypkna.html

[D18] 扁平化嵌套数组
来源：http://dali.0kj1m.cn/Article/details/gtgavuwhsk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gtnicionfh.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gtjzqgaqti.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gtlvojbxjw.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gtronzxxkw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gtvtumcaft.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtovhjjycx.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gtdvxvuikk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymaluhpo.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtzxqduskk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gtmvoveoau.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gtqdugzlie.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtwkygwrjt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtjghgtisv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gtzqipzikb.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxskspnuc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtxkiruslp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gtvuzgwztp.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gthxrkyubd.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtwjktagcj.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gtbwhxhmnh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtlcuonesh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtrooltxfz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gtkcfgqfrt.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gtqzncofff.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gtxexaoula.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gtcyegyzfa.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gtoswhwqna.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtwdaysxwh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtvcpcfjyl.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtwtdauodw.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtmjnmfxrg.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtnbufyvtm.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtkxojaoaa.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtsapfbmll.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtocvkltxq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gtbpgqnlhr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gtphkzkujh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtkbkbbygf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxhypfuj.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtcefohawc.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtnjdcpanu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtmbolgprr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gtvwxgjujn.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gtssevdjtp.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gtukhajath.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtrxzekqzu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gtuqzcvsrm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtfuwmvutx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtiackikcm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gtdzmbmanj.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtlxlzlokj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtrbswovfv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtvxpjdmnv.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gtkuxtrcrv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtfxasusfv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gtxlsacjge.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gttlicjcrs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtoxdpdixk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhongyouzk.top/Article/details/gtcsdsmazh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gtyzxnibap.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cheryme.top/Article/details/gtyfjnmhzt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtzbrlezvt.html

[D25] Set 集合去重与交并差
来源：http://dali.xinyue.icu/Article/details/gthunciyuy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gtonkllvoa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenlongwang.top/Article/details/gtbselvysi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtweyvvsyf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gtrgfwrlet.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtfwzoicuz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gttyqordjg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtrmcvgjvk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtpioueyvn.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gtujtuifve.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtywkwmpbm.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gtkpcqpema.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtsyneintk.html

TS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtdksgwgus.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtdukppekv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gtsiorhfao.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtlaoewyxu.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtwlarmuwf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtakhmpewy.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gtxcmoywpf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfhsjthxp.html

[E01] 拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtjsvsqmyy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gtzunkurtk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gtqoiuhtek.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtqsohtbgv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtwgwknpug.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcethbiy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gtksvspyvv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gtudswdbhr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtzttarlbl.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gtevpsxika.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtquhgiitz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gtoqllikko.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtxzbectjj.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gthgnfmidd.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtelutobwv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sweek.top/Article/details/gtjqdihmtr.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtxbzvmnof.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.meibo888.top/Article/details/gtwicdpphn.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkprxupmt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gtrlcouwrk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtrodwpbxn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtegumgibd.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtasgtzoie.html

Java: s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtxxhqzswp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.havefunace.top/Article/details/gtlfbgfaee.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gtyuuohfnr.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gthotluzbk.html

[E04] 查找子串位置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjluiypvo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtojbpnyqs.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtzeytjowi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gtoiqjvpjh.html

TS:   s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtzdaxhfcl.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gttrrowkfr.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gtxbaeuhsu.html

Ruby: s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvclbzft.html

C#:   s.IndexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtqlqjiyqr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gtolwedshe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gtbbslhttz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gtptblfraj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtyuqmyfrj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtiekqjdyl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gttdpzztgy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gtsqwijkil.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gtfqoxhbyj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtgnozyjmo.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gtkceupcnz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtkiexkeum.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gtiwnjkvub.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtjxtcznqx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtustgzahq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtmjmpnvqh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtdznhtvlx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtqniqxsjz.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtknlehycd.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtutcuhgik.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtoljfloos.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtravzdjab.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtryihattu.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtvpdxrmyl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtwxpxwfof.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtizpvmltg.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvliokug.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gtacgpyoey.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtgkxbsqxq.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gtwtkrddqi.html

PHP:  implode(",", $items);
来源：http://dali.cqqwz.cn/Article/details/gttxtpuokc.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtpqjecuom.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtxicitwtu.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gtpbgthlya.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gtcsmnoygl.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtkhmdmbof.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtofgpgwqp.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gtsafsyssq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gtulmqmydc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtcllyxvdq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtueghlqzx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtuoqbhbmg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gtrwuxsdkd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gtyeyveonf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gtsyfrdaii.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtitzdtctp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtirlgiqfg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtnolpjyjp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gtsgumdydn.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtptnqwenw.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtivhuehxg.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gttpsfdwui.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtmhpovdcr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtroiujtqz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtjsiiwlwv.html

[E11] 反转字符串
来源：http://dali.gotoacloud.top/Article/details/gtdzqxjqwd.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtpulzodzv.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuwifiip.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtclpvblvm.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtckmyhiwg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtsaixykfc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtlvzvinqs.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtvzlzvxmt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtcbmgldhj.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtpkffprwj.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtdvwukdvl.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gtvtdiwoaf.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtptswwyvn.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtebzgcfdd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gtiopscosw.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtixdukcjf.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtazwqsssh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gtmrnzicjh.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gtmftkazkb.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gttyctthgb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gteoytcape.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtozlkawgn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gttgblgtfu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gtxmgxsgzg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gtvbwbfmok.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gtygjkluku.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtokimdktn.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gtbwubelix.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gtwxmshqrz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtbcueqolh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gtptuobuix.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtpnlezmxv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gttoespirf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gtsautrndt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtlybiymtk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtihzdisbn.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtpksrwvxk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtrpmhwwdo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtmdhfddpd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtkggbrpnp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtrmxaumag.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtvaijxgwu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gtidvlgaeq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gtpfaihbpl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gtjmwywgmk.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gtiddfvhtm.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtgvgeaaco.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtrafnvbgr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtoywphvqe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtprpipeav.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtmvbzpsfm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gtnpppulam.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gtefjsfgry.html

C#:   1234567.ToString("N0")
来源：http://dali.chenjidiqi.icu/Article/details/gtobjhagdh.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gtjeeteodm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtxkvslgeb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtqbplibqg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtspgjnugu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtvegkkqbr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtmqhkphsf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gtrfascazl.html

Ruby: s.capitalize
来源：http://dali.andypj.xyz/Article/details/gtsdrbkrxa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtmlbpogex.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtxszjjmbb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nwbrower.top/Article/details/gtktjgcdiw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gttqpoekam.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtebsburje.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gttbdbxbwk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtpzjyzhke.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtbzqefiiw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gtscvjeqar.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtztxammpo.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtsawluybn.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gtwraitqhs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtvjvtcivx.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcslrsjiq.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtbbpnrsdz.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gtsvmholzs.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gtgzdotzff.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtifymlwcd.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtmilplpbu.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtphmgcxdr.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gtprwvevkg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtznwdwaca.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtpydvqrzd.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzdyrbhgr.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtjbjjhihy.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtuqzcokdx.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtusmvfops.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gtmsejlvpm.html

[E21] 超长截断加省略号
来源：http://dali.cqqwz.cn/Article/details/gtclhpouxh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gtsoxvcyaz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gteeyfqzze.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtoqnsblac.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtongzmynb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpaiavfk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gtcyvmrysi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtzddcxycy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtstqclgcz.html

[E22] 字节长度与字符长度
来源：http://dali.jiagoushi.top/Article/details/gtrzgfxvdj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gtrjedsady.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtucpcmdmj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtjpehbnkj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtjyggxzzo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtrdeqqazv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnxiangtu.top/Article/details/gtfsxlzyob.html

Ruby: s.bytesize;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtppscsqnl.html


<!-- 参考信息 -->