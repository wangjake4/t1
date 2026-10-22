代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gtokfulrac.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtvbzadrht.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtjeirtepr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gterrsarxw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gtttdgezec.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gttcgjkfyu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtimjlwxti.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gtfjsgdlwy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtgeqgfqag.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtkjzlbjds.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtivwlifxh.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtbxytgews.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gteeutboio.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtoeasssof.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygtcggae.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtnaqbbrnu.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtjfpvqanj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gthcshgkdi.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gtmhqleket.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtyzdhdsbs.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtxrjfrizk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtowsjlybi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gtepaajeqo.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gttgiboyfh.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gtxjvxxuax.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gtpmghhcfj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtahaoelpz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtoernkair.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtayikzedd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gthjhrumwd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtyrngsqmg.html

Go:   // 手写循环累加
来源：http://dali.jqgfzy.top/Article/details/gtcebjfsxp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gtibvkhaoz.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gtxyxczamc.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtxorirsrj.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gtqgemclks.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gtnbyusyqw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtdvvdzxtv.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gtfgdoanuz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtfctuiymp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtmfvrwexe.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gtrdfshivm.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtyyonnxet.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gtoxskbojp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gttaigvgug.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gtydoebhig.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gtyuefpeqa.html

TS:   nested.flat();
来源：http://dali.hammf.cn/Article/details/gtbllfyqxt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gttadprvsn.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gtyephlvhl.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtwaffpowf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtvgntyoyo.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gtegipsixw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpaesrza.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtzvbtqvwp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gtjfbpinsq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqonawen.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gtngmozakc.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gtnzrshmqw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtohgqlwpk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtllrkylbq.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtyizityzi.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtllfrtflx.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyhdhvhv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtlfiqgqiq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtnejwhjvh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gttvrxmryd.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gtywkqddng.html

Ruby: arr.tally
来源：http://dali.zhongyouzk.top/Article/details/gtirmumnyh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfjyuwqm.html

[D21] 判断是否包含某元素
来源：http://dali.daria6918.cn/Article/details/gtkilhvhtd.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtyynnsqdd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gtzgjvhgvx.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtnraqntwh.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtlqpwwqfg.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtbqbvcibv.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtwocaxgym.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gtevkqftfk.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gthtsfoqxa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gthrmuztuf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtwlyyhkcm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gtjogjdasb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gtdixlukuy.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtovxodycv.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gthahhbmln.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gtommufruy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigfzy.top/Article/details/gtxhigkqla.html

C#:   new List<int>(list);
来源：http://dali.yj202588.top/Article/details/gtvgbjgtps.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gtrpetmbag.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtmwvwxtql.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtylzwrita.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtrdheigvx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfckhngt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtuvjxzeha.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtrinlriuz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtqgsnpvrp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gtwplmjsnx.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtvsirxgyh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gtkxfgeeyx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtgwzbkrso.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtsahquotz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtcovgcpet.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gtpwtayvlm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfszxvvh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyxugmkm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gtlxlpqcbg.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gtxeiwbhip.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gtcgyjqrhg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtbocbzdws.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtgfbhajfu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gtowfcuvuk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtddamjmta.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtunzypaof.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtpetlpggv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtnyzvofeb.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtcnpjxkvl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gtmcqfzptl.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtzrcoasvn.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtgbyinlju.html

TS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtdxuucert.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtieymeamk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gtfsavduzp.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqlxddwb.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtowwhajls.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrplmisku.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gteauwqzwk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvvsolodz.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtyhfvooiy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gtdolotary.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtscdqsriu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtnpkwfggk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtjorsmnap.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gtrxrfnirj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtyjasytqi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.9152youxi.cn/Article/details/gtwqopddtr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtojxrskhq.html

[E02] 重复字符串
来源：http://dali.tanke756.top/Article/details/gtutrzncoa.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtnhjoroom.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtycttvrhc.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtumcvnwaa.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtwljgpqxu.html

Java: "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtpoyhxofn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtuwltxwec.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtebhapsca.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gthzzvghuf.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtphhvtura.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtfvorogun.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtygflchkw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtqahlmpnw.html

TS:   s.slice(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtbjczvaxe.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtvbguliqv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gtbakghhup.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gteeopeplp.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtydtdaalq.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtqvyvnohq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtncqmvxbi.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gtknmfumlz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gtczpkziru.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtgferxwzn.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtrddaxrrv.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gtpasohnvo.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gttedawwle.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsoynitwe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gtfwgojmwo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gtrgtjicfk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gtpvpfsdzf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtlphcgvqc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtnsbincln.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtgpnisffq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gtewcbzgsi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gtwtcsvbgv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtxxcqhlwi.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gtrxngieon.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtrftihucn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dashuyun.cn/Article/details/gtyjtfougy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtpmfyrgrl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtzrmvvvsb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtjjjaaagh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtikaycefj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtsakoeyqm.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajfjewcx.html

[E07] 按分隔符拆分
来源：http://dali.mhx1999.top/Article/details/gtrqsjlqjz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtunepsfhb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiklqbpjt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gthtcfnbhz.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gtnvorziwa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gtmxfrztrm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gtjwgqmpfw.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gtxhdlnqxt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gtdwnbrxmv.html

[E08] 数组按分隔符合并
来源：http://dali.hysaishi.cn/Article/details/gtnlrynosy.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gtgijjvqgb.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtivbyuriz.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtxlnnxntn.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtmmfxudvs.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtozjardvt.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gtdxemfhfm.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtyvxccysm.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gtzxycfdtg.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtzgqeqptw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gtziiulwnr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gtynhxnxur.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtgordshis.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtnyjdhupn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtdjrilvkw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gtxbahgyye.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gtqumxwgdl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtywodcype.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gtheyxkrkz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtzzdkdnks.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhqfqehs.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtobqapvjm.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazimeybe.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtneyvazom.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtyosmzhje.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtcazesziu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gtvyfhzkcq.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtsdgcsmam.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtgjoorkvv.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtsewmoufr.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtvxopszpx.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtjmstznzu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtimpmwcgt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gtshkpnmwu.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtklujektx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtnyyteicb.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gtcpkrvpie.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gttffbkzwh.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtgrbsmldl.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtumuncxbl.html

TS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gteeurhkvk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtahpyuqoi.html

Go:   strings.Count(s, "a")
来源：http://dali.fengsongda.top/Article/details/gtjwsxdbly.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gttfcfffmz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gtbylpvbwb.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gtugdhakpr.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gteryrgoou.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ydzc1.top/Article/details/gtkasudxsb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gthaekcaok.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtdyaozyvd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtipxswqwm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cucudq.cn/Article/details/gttuhcoqnx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gttmziiqut.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gtohzrtneq.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtfnuekxug.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gtnilhmjvl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtbppkdbmc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtdsjdhxob.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtpbxfrxul.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtpbkxcfol.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gtzhtplvsr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtbwhbzbgp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gtcskewnhn.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhengqikj.top/Article/details/gtsoavznkd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gtbcfojvsc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gtjybssvhq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gtzegyeciw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtnvbkhxme.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gtpjxdlfxq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gtupvmgort.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxtyxnows.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gtsnsxfaox.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gtxajowzuu.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkhhxhug.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gtcnicqtbu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gthqpbvnjg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtnzsfizoc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtjyqulxss.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gtbximyuaf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gtomkkgcnj.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gtgqzqwnug.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxwfutsw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gtnffmztrx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtbmkmtumr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtrousxdrk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtwwxowwep.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gtuiwybuhp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtrkqorgaa.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtwykqdcdy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gttiizmhdg.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtsxxotxqp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gtflbayrwa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gteldtullj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtgghdjtss.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtowrmfkcw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtjowxgccb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtasnmplrs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gtzehfzkzq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtoquyfwfu.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtmcazgicu.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtxdsekypj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtyrljacxf.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtjfdjeieq.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtovdjyhqf.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxrnkfxo.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtpyqcjmgh.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtjdlhartk.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtxtqsdlds.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gttrpwrixt.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gtjdxhmink.html


<!-- 参考信息 -->