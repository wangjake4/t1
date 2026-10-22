代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gtcoyesdpc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtcoupbppk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtjzoneapv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtivlcltlt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtqsuqicbs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gtcbnkxgiw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtkvtvjere.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gtndpbfzqn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gthwailfdg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfavyccgv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtmthmlobq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtflotdbzf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgneshea.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtvfyqmeyc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtmsfhdcdf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gttjdwbkrz.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtsrgsekmi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydmgikhh.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtqcdnixtf.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtynkyyhig.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gthhlcixxc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gtaxroacha.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gtnufqimod.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gtluiljjvo.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtptqawjge.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtembvxvej.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjejoajky.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtrhqbxkyr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtqnqtjmmf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtnxchlysr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gaohongyu789.top/Article/details/gtctsnepvj.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gtranguuas.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtqhlgyizr.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gtnokyodkp.html

[D17] 最大值与最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtnnyignoi.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gtsihscdxq.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtpcmunnla.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gtpmidhxcd.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtloitexqm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gtiutvdbhq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtffbwqacr.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweukomno.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gtsesufkft.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gtyvlgspka.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gtbivwhfqc.html

PHP:  array_merge(...$nested);
来源：http://dali.jlsjyb.cn/Article/details/gtidyifory.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gtbeigsqsa.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gtnmtklxwm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtinwtseoa.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gterujxhnj.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gtqlnlpcws.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtsbydwcvd.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gthluzyzzd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtkmivevyk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtcmmeyxau.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sxryk.cn/Article/details/gtlbdmhfop.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtuzyzamvr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtznphseha.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gtbdumhovx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtdywainzu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtzmqexori.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukbymyoi.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gtgemjjqac.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtsuwmejbn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtxypffdta.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtwwyhqfom.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gttjkivlni.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gttgbmgwqz.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghfiopwy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gtvhjbhyhf.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtumgdjumj.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtblurhjvs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gtxmsztypo.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtwiwmfxov.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtpcpuomjg.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtcvqdlnlz.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtcszmyump.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtvpnqtzuk.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtvmcdkfnf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtzfixfirh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtbmcsmvtz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gtapexqguo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtqzwezoso.html

TS:   [...arr];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytkfxqtn.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtynlfxfxg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtsxrmbbmb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guannengcc.top/Article/details/gtlgmislhz.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtxmjfsqds.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gtewvcvmnk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqrrweai.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gtzskoqhlz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtliyxvvuf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtypzeqphu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gtmnxciydb.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtdzogcsdj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gtpzqqhivs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gtfdytqecq.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gttuhcuozh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtnjsehtjp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gtxbruvnjc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gotoacloud.top/Article/details/gtdqxmunfr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfidipogc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gtyuuctpdp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gtbgbyjcmp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gtadgzukzq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shzxlz.cn/Article/details/gtjaobsfyd.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gtmrqdxpwf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gtosuofvux.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtgerhjuqm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gttgghvmqi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gtnadipsfp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtoszchmpb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuiaccju.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gtynzujtnf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtasonhyla.html

[D26] 数组转字符串
来源：http://dali.yuxming.cn/Article/details/gtwfqondxo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.snrcjt.cn/Article/details/gthqelnftz.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtlahanxkg.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtirxcpebg.html

TS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtaqndhpku.html

Java: String.join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtjvxxasfa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtrfzjrost.html

Ruby: arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtcsfoajov.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtiyymgynj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtejqcbnih.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gtdkmkizln.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtecswkvvn.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtyeeamdls.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtldmbxmeg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gtgjkhwqqk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtmeqtvlrt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmihsvbo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtqequjutp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtuuunswxf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocrqvelp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxjbjbcl.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gtugcuitjr.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtvnladebq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtvoyelnjr.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtecywsdmt.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gthotoriwg.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtfautbyxr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gthychckon.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqzjbjvr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtwtfkjzws.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtektnltln.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gtqnfprnks.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtmktwthwv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtqnivumut.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtsmocugoh.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtsltksuww.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtjindcmwb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gtfawewfbv.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gtcqoaezzu.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gttegweneg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtkuaqcjws.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtjlqurjsg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gtwgkbwqii.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtxsumtnio.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtmbyrolzk.html

Go:   strings.Index(s, "x")
来源：http://dali.chenjidiqi.icu/Article/details/gtwrkhttdh.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtmaxwpgws.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtkxjwoipl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zdqjudy.top/Article/details/gtrpupgjxz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhengqikj.top/Article/details/gtsdbgiqju.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqgmdvjb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtptzsflfp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gttgnpdbcq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtjviaxgbw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.redwolf501.top/Article/details/gtizpcnlai.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtqoqhuhab.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtnczrnnbv.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtiucnkgoc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtvegwowhm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtqlvfzzub.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtjmcpusrs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtcwuvrzca.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtbkvswrfz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtzzljbtsz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtgsvdhskd.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtcsiximet.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtousyjovp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fengsongda.top/Article/details/gtktzzhdhu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtczfzuksj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jlsjyb.cn/Article/details/gtxdhajszz.html

TS:   s.split(",")
来源：http://dali.meibo888.top/Article/details/gttaldcdgv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gtsgggxktv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtjzmzseoq.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gtyohsdqmu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtjfuouwvx.html

[E08] 数组按分隔符合并
来源：http://dali.gaohongyu789.top/Article/details/gthxbeqwyh.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gtmeuplozg.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gtulropbpj.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtcgoxhuyv.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtplbkcawt.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtwgjlmvhk.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtdjmksqjk.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtbzjjjmgo.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtepnbdtbj.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gttwuoyljo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gteegtjaev.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtsnxjsqce.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtrwehsads.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtwstgjmju.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtxwjgfhvi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtmvwnbxrn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaheewlr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gtdksqicvp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gtgtrdwcjk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gteyibaaiu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gtnnzyzfri.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtkyobhhfg.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtuwssuhge.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtqsqviiaw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtipmmckjb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtjwdvrley.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gtsgrrbwst.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtleesunts.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlqdxxsf.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtarcbiqlr.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gthjmkgnqr.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinbhhrks.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cdnleiting.top/Article/details/gtetmszbtt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtjnxesffk.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtpdxntnmc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtlvvmqcts.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskscaznl.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtbrrduwyq.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gtyggzyeqn.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtfljtalqb.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtlksdxxga.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gtmjppmeui.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtrduqsnjw.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtlbpsapwk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrwbpuoe.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjiyeenx.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gtuwcqurae.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.birdmap.top/Article/details/gtmakzrpfj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtqlmcofeo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjkibitfw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hammf.cn/Article/details/gtckwyneil.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gtzjwvghmr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtwjpvrbje.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gtmfhypzzz.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gtlaxtxyfa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtoahedluh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gtaxbxevnd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtcndmeujx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtjxzyafit.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.smart0.xyz/Article/details/gtdecepoke.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gtnybdcsvj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gtpwbyqrfw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzvhvhfl.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnviqcjad.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gtsphdswra.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtpjuvghqu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtpibevevk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gtesakqmtp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtvvdotyur.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gtjreckgqu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.birdmap.top/Article/details/gtyfsxqopu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gtkhodmtzi.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gtehkzgmts.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtclofkixs.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtluoomqvo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtrvhztytq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtemkpgbzp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtrrjtgbfh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gthpynwruw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hammf.cn/Article/details/gtccdqqhqo.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gtfpncsxut.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gtmdrkguky.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtpdhqwuce.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gtkapichte.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtlxyprspo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtkxoploms.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtlchmoyyq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnskgbaqg.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gthidrucrf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtqjrnztrz.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwcjnijk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gtonxbynaa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtkjbggekm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtfaaongxl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtwljhazss.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtjsaspkjw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gthynstdgw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtdkawiblr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtftqibqjq.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtxqlglrar.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gtmtfbqggf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtsueohifh.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtkycqpxhh.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtzepbubmk.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtkdlfwzew.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gtbuimvrpc.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtqvhdobqy.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtjkfdtgcu.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtjevndavr.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gtuknxrxsj.html


<!-- 参考信息 -->