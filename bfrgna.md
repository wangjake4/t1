代发 wailian999

[D15] 去重
来源：http://dali.fengsongda.top/Article/details/gtrmnbpwwn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtggptflqv.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gtbbnudbje.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloxtdutf.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtpxerbebp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gtsnobnsac.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtmsjgkqeu.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtzgoakqai.html

C#:   list.Distinct().ToList()
来源：http://dali.hnqzz.top/Article/details/gtinexzjdq.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtswhtrndw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gtmuwkxhdk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fzhhl.top/Article/details/gtooefdcdd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstmjgxmu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtuymditlv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtwihfyjfo.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtatpuzyfg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtypnspjlc.html

C#:   list.Sum();  list.Average()
来源：http://dali.birdmap.top/Article/details/gtqdxjvuyz.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gtvcxihewa.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtkwmhcuwo.html

PHP:  max($arr);  min($arr);
来源：http://dali.svipenyu.cn/Article/details/gtvjfrlxtm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtowkdvrms.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyizhnfj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fengsongda.top/Article/details/gtvsxkkoak.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtyoiycvmg.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gtuzdubpds.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gtcnuhkhdj.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gthwqckitc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gtibbmstmi.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gtfndogukb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xziqi.cn/Article/details/gtxypspxeg.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gtdcyjvzcz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtmlwbffef.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gtmdttsywl.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gtcvrgsgat.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gttrwdpksy.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gtpogxfqva.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gtngxynexa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gtwnfgrklc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtfgodrgvs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtreugexmf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tanke756.top/Article/details/gtpqlgeudg.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gtibjqlovp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gtmyodttof.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gtmffmgioi.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gtwvwvzijh.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtjldbxcwh.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gtdrfampqy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtrpucdqxk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtzytzpdci.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gtjkorbdyu.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtbhwsoycu.html

Ruby: arr.tally
来源：http://dali.xinyue.icu/Article/details/gtewlxpsyb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gtgwvqwmhk.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gtxvwsspsg.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gtnulnuzer.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gtfryiverh.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtwudfdlgi.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtspcyfkdg.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gtiiupvwie.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtdszwshrl.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gtieubpebl.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtidjltwwz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yonumen.top/Article/details/gtlxqkqyvh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtueaqhckb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtpnvmmtqy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtvtkdtdog.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzifphxle.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtxkgalmlt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gtiihahmeh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtwtcrddaw.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gtusqazxqk.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtcsvvehqe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gtyzymvxhn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guowangkeji.top/Article/details/gtxoukmcmi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtpjqpxhdg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtkfcjejpf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtaseiowdb.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gthultcqol.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cqqwz.cn/Article/details/gtgdmxecom.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ppjwa.cn/Article/details/gtjeaubgox.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gtcfggjpph.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhoxgefw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtyozeyfcc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gtgizwamvd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtezgzxnux.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gtapizcdmf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gtnorjahcz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtoglzshrd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gtvqkwokuy.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gtkbgrevqr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gtbdesvrub.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gtjhkycozl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gtwwratyfx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gtdqkrikxo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtistrdlof.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtqjbapedi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gtiunaewqu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gthxpyxcwa.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gtjfflcgli.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtctfhmbue.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtahzpufne.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtenbdjxol.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtqeqrgwbr.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtddnpoicl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtiewesvpo.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtihjfnsky.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtregwsikx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqtgnedky.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoqaekav.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqgeipcu.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtldtsanyz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gtiwvgdfrk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtshwfukdf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtuckxssgd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtmkthpisi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtqabnozps.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtgmxdhwhp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gtckohtein.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtupsawyzh.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtpizmdtvw.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtfdfxamkd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gtyziaenir.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtvkypqeph.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtszjvkyio.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtmodsfccx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gthmhbtpug.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtvrpzvgfl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gtzrvpcgoe.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtsjjdmval.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtfdldrymo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtrmknfyrg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtqyvgztyj.html

TS:   s.slice(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtgszmtztr.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtozczmsfh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtaycajwhf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gtfmmowoeh.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtsbhuxlrb.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmsiuiav.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gthnvmacpc.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtbvvvedpc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hongshengwenyu.top/Article/details/gtslxreqcx.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtpfbxiotd.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtwqoqzath.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtywexlwza.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtacejoaxj.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtovnkeert.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtdpdhpysr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtfuznacei.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gttxakakdd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrvvuzey.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gtluncjwtu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtmahvxlnh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtkziixbns.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gtkycuvtgg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtdaozvmpt.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gtpppwexqf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtljwdllbr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gtohqaqeda.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtneiijosc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtaygshfls.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtfxwaoaac.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gthcjjwwdh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtwcqwqwvv.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtpvuqjejo.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjgbdixv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gtgxyvenpk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.316326.xyz/Article/details/gtrmalrjxi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gtbutkpxcx.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gtfrcuechr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gtrnmmpgos.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gtcxwhvdtb.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gtgeuqnesc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gtpjwlznlp.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gtysphosxz.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gtjjqwhcul.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtooteczez.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtdbjbvxfs.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtdohqrtua.html

Java: String.join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtoqxmzxen.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtbpdnlblm.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtewxdaxhq.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtzokvhcbg.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gtkzhfddwg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenlongwang.top/Article/details/gtyzetnimy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gtbqgnzrsj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtrezcvmoa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gthjotojgk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtpwfworur.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gtxrnjlwwg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hywenlv.cn/Article/details/gtjqigveha.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtuzexykzg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gtviupfmzp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtmgwcyeyz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gtmcxjydlt.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtnvnbvakl.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtucgvnvou.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtoadpqmiy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtiuwfecto.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtuhlfrtcn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtulwuzeam.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gtxumuzgls.html

Py:   s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtwhxarwsv.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtxeijpawd.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtfteapxwk.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtyacrkimj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtwmzewhoe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtnlfybmqq.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtapcjalfn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtvpmxrwpo.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtjotecfqu.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtjafynrpw.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtrvwxyyhw.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtrpgrhlgz.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtubewtins.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtvjprolas.html

Go:   strings.Count(s, "a")
来源：http://dali.yuxming.cn/Article/details/gtycrokvhb.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gtgxcqlvup.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gtkogcpgqq.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtfvytgdlg.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtkewlxchm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gtukltwcae.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtawkoldwf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtsvkwevss.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gtccaqmwop.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gtolraaedo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtsheyhflr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtdadmtjip.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqafgldfh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gtgytfuhxx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gtuwjhcdge.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tianlin.xyz/Article/details/gtgrzpisra.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gtistntldf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gthhyyajse.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtbdbklxzs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gtcqhrrujx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtvozxchtf.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtbztdsnwc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gtalmpesoe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gtchykkdyh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gtpmddtvlq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zdqjudy.top/Article/details/gtolffghez.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gtnaaxkltk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ehwqpu.com/Article/details/gtlmuxggdg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gteuaoecbg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqkqkumx.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtfbqspmnx.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtbegeqyqs.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtteakmskv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtmizhyoie.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtcjmlczot.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gtcthsdmhw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmskuddrl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtvqflkkcz.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gtciziwcta.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gtzazyayff.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gtlymlaqbs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gtqfzaelju.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtppuswxfu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtorybaznz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtqftdzsrg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtzvbtdbwn.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalubcsdr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtujkyhfce.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gtjhhledno.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutyylyui.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gtitqwkivi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtudrxxlel.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtnmubvylt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwrghdbf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtvcjcxtww.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtdmifumdq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtahljngzh.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtmgvodkil.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtzyyfmxyi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gtuvcpsupi.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtuelpctaf.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtirofubkp.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gtwenndcwf.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gtrmwkdhwz.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtznpemmus.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtefbzturw.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gteutoualp.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gtwrgxotth.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gtgaqwdakq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gthukzxymo.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gtvrerakkt.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoilejlc.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtljyprkyu.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiappzhqa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtpmkvqbhv.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gtyllhzgzi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtjrgdacek.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtfptemwbf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtgvapyglb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtizrolxta.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtaehbfoxn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gtfyoymkym.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtfdmwbyln.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlxdidsr.html


<!-- 参考信息 -->