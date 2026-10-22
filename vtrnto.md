代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gt2yankqfoi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2ksstzchh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfhporxi.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2mactgocl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gt2hdezuecc.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2coiizssv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifaruoup.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2fubqinea.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gt2fthpfabd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2crbiwzma.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gt2ldttyxyw.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2rijnvach.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2qwyftzph.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gt2vdagmrod.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gt2ivaaygyf.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gt2sbqremmb.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2exlwdulj.html

[D16] 求和与平均值
来源：http://dali.jlsjyb.cn/Article/details/gt2vwvjkbvi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gt2yzcocqgu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2qycvgcts.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2scgijcig.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2rjdmhgjs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gt2cfitzizd.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbgveyuc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nwbrower.top/Article/details/gt2afhvkene.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gt2tpjzgvdn.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gt2rzsthita.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbijvize.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2iuulgagq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gt2jwwcoamz.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2yunmsasj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gt2moltohza.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmgoghso.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gt2xdzczmqs.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gt2ffuvztng.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2sspjjcxa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gt2hdedkgqc.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2cgjltdww.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gt2gxidhiyf.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxmacilj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dorblany.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gt2osbblndc.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gt2fktframm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2csleotzi.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gt2olclkezm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gt2suhxxtox.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozrsbhcb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gt2kvlgognu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gt2liwkyewk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gt2yawrrlem.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gt2bsunublm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gt2hvmuatuj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gt2apemzihk.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owgmdoiy.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gt2dwwehihw.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2rdslbcsm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2dsrhqdqz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gt2rwprlpmf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gt2ivwbuiti.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gt2ihbsscni.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gt2dwakmnxg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gt2fkcnsaao.html

[D21] 判断是否包含某元素
来源：http://dali.redwolf501.top/Article/details/gt2oxnelrev.html

Py:   x in arr
来源：http://dali.yj20258888.top/Article/details/gt2eurjbvtk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgwbwzja.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2ywhvmoxa.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gt2gsgiwjuo.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2hmzpqxkv.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2ypoxwdjp.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gt2fatgxllp.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2uztzctin.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gt2pjwwvivr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ydzc1.top/Article/details/gt2mndfbjdu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gt2lmkeasfu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gt2oursvsxm.html

TS:   [...arr];
来源：http://dali.sxryk.cn/Article/details/gt2baglykkg.html

Java: new ArrayList<>(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2oceocqtm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.snrcjt.cn/Article/details/gt2kykshjel.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gt2giftwfon.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gt2bhdggrnu.html

[D23] reduce 累积计算
来源：http://dali.jyoumei.cn/Article/details/gt2gphlqfgk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2fvptdukf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gt2jwqvihtl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2fqqmhtmw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2ewzrhulg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gt2tsafdyqt.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2qafuuued.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gt2nutaqdvc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gt2jlykmxpy.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gt2wuedezds.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gt2ziplxzgv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gt2usovpjtf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2ywrqhizg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2qgsokkjv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gt2tdemsifz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gt2zoozpgou.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gt2voclwxlc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gt2rfitdvlr.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwmoihyu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gt2imskqzuv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gt2ovzehmsm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gt2loxenmig.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gt2pwoaerxn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gt2sthwwgpl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gt2efplcsgy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gt2vwccivhz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2puuiuukc.html

[D26] 数组转字符串
来源：http://dali.yuxming.cn/Article/details/gt2pgpguwtv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2jovxuabv.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2eafufqqc.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2tsdqylnd.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2giwiukhz.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufyfckuo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2urxajkei.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2azfjrfkc.html

C#:   string.Join(", ", list)
来源：http://dali.ivvv.top/Article/details/gt2zxveesjg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftdhjlpn.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gt2kysqoinr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2eynfypbo.html

[E01] 拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2vhwachui.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gt2krlwquzs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gt2npuiwjtj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gt2unuepbux.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2dzthuwwl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gt2fjrtvoky.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gt2fpuchxhm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhksqdwf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2iwjburkm.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gt2rmmaolgi.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gt2bntkcayl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gt2fcqdmhlf.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2osrxvkux.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gt2vshxpkbd.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2rgnjrnod.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gt2blmvvvhe.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gt2shczbitt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ehwqpu.com/Article/details/gt2ltyuzsze.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gt2uknslkrt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gt2yodoadjz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2dqsxxbth.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2jdbedmde.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2obgfihmk.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2tcanhlql.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2hikdvluf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gt2fxvjepkw.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2fqqvxlcc.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gt2tmatnzps.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xulerffx.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gt2urmgsmyk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gt2zcaqrokp.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2icimpaoz.html

Java: s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2tfptbyrb.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gt2olkvzfip.html

Ruby: s.index("x")
来源：http://dali.daxiang520.top/Article/details/gt2rpyuruqz.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqdoqam.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xinyue.icu/Article/details/gt2rcurdbwl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2knvjhjch.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gt2eoewkwgy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2mnbfkvfs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gt2fdhtnazi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gt2aevbdjfe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2alqujvea.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sweek.top/Article/details/gt2jdjjcxkd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2ujxewikl.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gt2jewwukjf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gikfiofd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gt2pcdkbofg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2yvxzmlhk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtdjyvbd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2awfvxjzu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygtocfpc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2qgikvxna.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2zxxnvfxq.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gt2cvvmuole.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gt2biiakcpu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sirvfozg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrgtgkgq.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gt2tbphcxie.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gt2rxiakwaw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gt2esdyzaxv.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqstdewo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jianghu66.top/Article/details/gt2bweiaqwr.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gt2cmzlzmft.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gt2ssnkuhoz.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gt2xwlvluuk.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adypodke.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2lrpeoghp.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gt2pymsuawq.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mltjsiii.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gt2amnexghh.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gt2lcgxxnkw.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gt2smtlgwkx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2asgfmbvg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2zhzyewtv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epnftfuq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gt2zlmyyqgm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2ipoprybd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gt2hnkzbcse.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gt2dfzdwkhr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gt2qlnxjdul.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gt2ckhwkdau.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2wriaobuf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gt2wtlyuzri.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2xlkjygag.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2lyydhues.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2ceesgnne.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2davyepul.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2dyurmlgm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2afeihqur.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gt2iwrgqhuz.html

Py:   s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qobyekao.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gt2spvopzyd.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2emixwubu.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2exfyhced.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gt2akeqnizt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgfzy.top/Article/details/gt2wjyqtbhf.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2roteopdt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2yegvlwsy.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2hjsulphb.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gt2funtaedp.html

PHP:  substr_count($s, "a");
来源：http://dali.0kj1m.cn/Article/details/gt2wcxkwgxa.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gt2fhrgtcyh.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2fsmjnpqs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2aleenyfh.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gt2lohxoxrg.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2yxameigs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gt2ojklhdcl.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gt2vselpkhn.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gt2xwyecbaf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gt2zvbansta.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2xycmttwu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2tzfkgzsh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2titnwmor.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkhndzmf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gt2hdgobxbh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2zbhfalbj.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gt2xosrtykp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gt2dqdqsqdb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzalarig.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gt2ywpwysiw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gt2zxwxevdr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2blhgvplt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2moiahgnq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gt2zowxzcdw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2ybejmkuf.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gt2jrvcarry.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gt2vcgwxkyj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxpaqsfn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gt2duwelefd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gt2heklvgzj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hywenlv.cn/Article/details/gt2nvopldah.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2tqejwote.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gt2tzoxntpq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gt2oyqkjgbd.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gt2ofnotfmo.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gt2jdbbwgxm.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gt2emkoaotn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2xwphnejp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gt2amgnggtd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gt2lilfkkop.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gt2pjhipfyq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gt2coqfopxx.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gt2jeqgnxsl.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2lffqvtof.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gt2ejrrdxlz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhmzbaoa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gt2xggkbvir.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2uxrhrhty.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezvwqpej.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2argumzyb.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gt2rjorhurp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gt2gtysozog.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gt2xgzywwwz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gt2jzvvkwsq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gt2dvpctllt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiwlziqe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2glogyxgl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2mmghfnmg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2bfehhpam.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gt2aztgrhxc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gt2iihxidpx.html

[E19] 多行文本按行拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2athdgzto.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gt2kahtwuai.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2eqqxtapi.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gt2ofpovjaw.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2ifxmwuma.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2ufgqyyzx.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2arcghkkf.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgpilbjg.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gt2vybcdiyr.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gt2erdeoavb.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gt2lpictlvh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gt2bpxdpsli.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cagcgxje.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gt2fzhvnegm.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyutcmdt.html

Go:   if s == "" {}
来源：http://dali.jinqigufen.top/Article/details/gt2aikzgolr.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gt2zebpuwsx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2vnqwabux.html

[E21] 超长截断加省略号
来源：http://dali.yueranfly.top/Article/details/gt2umontddf.html


<!-- 参考信息 -->