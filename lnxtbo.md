代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtyezfcaov.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtgdiuimfd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gtmuqaygvv.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gtxntvlunj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gtggghvhbe.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gtryljndtd.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gtoesklkqb.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtbndddggk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtayvgjnuc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtstttoxit.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtripwdggz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gtcfjtlybw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtcdftusfu.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gtvepycxto.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtsfgyvktd.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gtmaytkzph.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gtgmkuxcog.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtcswimemr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gtlhozthib.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtaxtdehhj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtknpnheck.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gtqokezzfj.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gtmxnnikzo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtgrsqyrqy.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gtqwibjxjs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gtytzbvjlr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gtdxvstfsr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gtidevquzl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtircsdpod.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtcnupunex.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtxizjuuei.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gtxxejacif.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gtcsrujvxz.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtylcolqqe.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtjtfnstzm.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gtnkcqovok.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtlqqncsta.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtfrluhauq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.feifeiyinyue.top/Article/details/gtjgynyqzi.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gtiftuyqfg.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtfafxbqjw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtzveyhcze.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gtifdmyble.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtnkctzzaa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtbhlbwotr.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtpdoaytpz.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtzjlsdqin.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtfwxblqxg.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtmvzweucm.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtgbwdcnjz.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtidqjwfhb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gtmqukfbeb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtgixgvhdj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gtdzaifvmx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pycfn.com/Article/details/gtmpxxbosn.html

TS:   [...arr];
来源：http://dali.feifeiyinyue.top/Article/details/gtmwydwjls.html

Java: new ArrayList<>(list);
来源：http://dali.xinyue.icu/Article/details/gtlrtjfoef.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtxqctovpu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtaistrtru.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gtxirgpycd.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gtezxhtzhg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtfgqbbqif.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gttukidbky.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtgtlcnacj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gteuwjnznl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gtbxhtozqo.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtpllqxczv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gtvxearmxw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gtizajvwhp.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gtwcciiauu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gtuucjrubb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gthaulcjfc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtykrhyutk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtxihhadok.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtnnwvqvcv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtrrypsfor.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gtvcvibimf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gtjrlrpbdt.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gtfkrexxhp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtkqnmmnie.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gtikpeslge.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gtvqgvxzsd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhkdtbdj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gtuicxjvyh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.haohaochexian.top/Article/details/gthwiigaoh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpmdaawb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gtsldnkgde.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gtcduzlwcj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gtcybzbect.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gtbobshcly.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtblmkcqef.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtnhfnijxm.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtgduwagjv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtuiitaosd.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gthwwyvlls.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtondwyvkr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmuwdhvdy.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtpwwpqdkn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrmznvkbz.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtptlopief.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gtfbzahlai.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gtvbwtandr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtoilcpssu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtanxxksug.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gtcflkkzcv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gtmpdzrlxu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnatxlewu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrqiqqow.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtfsgzsfmx.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtzfznoiir.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtnhyazygr.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtiispkjkk.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtuioncbvo.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgstayqlm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtxjfftnme.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtoyalffvj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtkfdquwhi.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtuoacowan.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gtmwgshybi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtzyqhitll.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtulfyrjos.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtbsibgojz.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtdkzqelen.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gtmabqudxk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.quarkkingdee.top/Article/details/gtnbscijvy.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtqivmqgcc.html

[E04] 查找子串位置
来源：http://dali.nanxinkj.top/Article/details/gtzzhgsyiu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtludxfheq.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtwpldqnap.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gtneepuoqb.html

TS:   s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtqtynvebs.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtmurjriog.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gtfkonnahn.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtzakftrly.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdqeymgk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gtxracfbib.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkdhrrbx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gtyfbiytks.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gttgxdcvvl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gtmasavhlk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtyadcdibw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gtthwpurci.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gtsojnbmdb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtmbfparxm.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gtvnsylzcv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhtcgquj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gtjoxdnlkp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtppfvudpa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtqkhvpwaa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtakycllup.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtiijjtfeq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtpeopjhgb.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtemfeuioe.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gtbxgzbkjz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.iojbl.cn/Article/details/gtdndvtfsu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsioynvo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.smart0.xyz/Article/details/gtqvjbtvrg.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtvdodywit.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gtlfiwhuqy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtxjxtadon.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gtxhthgtje.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtsliozgns.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gtfaqcxuyg.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gtacazfuan.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gtlybyapmt.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtqngiyphy.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtgjnsbgeb.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gthxztjafl.html

Go:   strings.Join(items, ",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzliyeply.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtgpgkqure.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtplegnxfs.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtfvharsdn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gtbfjnnfsp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtuhgyxtdo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtmzluzmdc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtvcxtdktu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtgibcxitd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gtpsxbqipa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xylfe.cn/Article/details/gtzwwhfxew.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gtssceuwqc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gtligmoejq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gttcsmynhs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfooxzkh.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtdscyzvog.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtlnxoyqie.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtrufnvjxk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtfsbwtlqk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtdrildjvg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtpjlbwopt.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gtljwohdsz.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gtdgwwenwy.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtwrllxssb.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtjjqnzcsw.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtvkajkauk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtbxjgbpgu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gttgiafwwy.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gtckckyeof.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtggclpjaw.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtfqvbieke.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtowwqpqlu.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gtxkfirajf.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtemxmicjy.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtryhqiafy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtanmqzfvr.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gteqmxfjtw.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtdnigiwyi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gtrqykbens.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtnhjuiraz.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtkoqbfdxv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtagriytta.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqoghrcfj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtknhxshew.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gtytspnrfs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gtslbcrdid.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfscvexsz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gttfttgkzw.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gttcnxtdvo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gtacnlrops.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gtssdmzmos.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gtfjuhggyz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gtcuyhjolg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtpmsfgjyy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtcfdczcyv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtpagwudiy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtkzwlavoe.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gtpkupscet.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gtzzzkwbxf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gtefcfcevu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gtrsnbqoch.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtxivyixbc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gtopgfeoza.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtfzlvkfvu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gtrzxwitjs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gtjmylnhzu.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtjdmmhduo.html

Py:   f"{1234567:,}"
来源：http://dali.yj202588.top/Article/details/gtszwjtwav.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gtfbzoiktd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtnpnbdagu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtwdvbmlju.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.c1oappe.top/Article/details/gtuqkqrhgz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxnpzljt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gtdygljrvr.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwcjywuj.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gtrpcxhnro.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyjgrzab.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtdkmasmdk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtuwtsfmcg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtlusikjdg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gtbdzvcodh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtgaoljinw.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtuttpddqw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtqrmgtyuw.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtqnmtfdaz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtfrfkkmim.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtcaudlgge.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtdfvftspo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtahtziylu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtycrvcuqz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtjvlvejie.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtmoyedism.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtptwjscce.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gtlmkfflvs.html

Py:   s.splitlines()
来源：http://dali.feifeiyinyue.top/Article/details/gtmgsljjlj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gtpfcaoimg.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtpycfveie.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtthcrvbta.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtfilxcipn.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gtzseqlskk.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtknjiwsds.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtgzwjncls.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtfseyapen.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtgcggdntc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gtvxtlayeu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gtvmxmsnrt.html

TS:   if (s === "") {}
来源：http://dali.jianghu66.top/Article/details/gtoomvrhua.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtghaenfyq.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gtwgsdepoe.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtwptvecww.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gtvbycerwn.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gtnudecbpt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtjuymjqtn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtrdqurlwy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtgnbkkvvp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtbhkgedxx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtsxkeklux.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gtbvlvvwjt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtgavltjeh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtpztrypyz.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gtlvbxqpja.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdfpsryl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuczixykq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtuavgeuef.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtwxwbjwma.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gttegydcal.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gtmgovntni.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtikkfksgb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtdihxcace.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjcgsffhb.html

F. 文件与目录
来源：http://dali.xylfe.cn/Article/details/gtrzvothuz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxxikrumx.html


<!-- 参考信息 -->