代发 wailian999

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gtvaexcwcq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gttadirikq.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gtfaajjpst.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtaxgmocdd.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtodzosdug.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtvrkcdzsw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtyffpwrkd.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gtfyfhikmu.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhcoqmhr.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtxtogkamc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtqqxyubde.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtjlbciwxz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuenyrnhm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtqghqxmho.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gtmlvctqyb.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gtiydguyft.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gtewdvtdrf.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtmondnjgi.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gtkupddadl.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gtstxlzsdp.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gtjswohfdp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gtmardiggd.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gtckosbmbe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gtvpxxbbvt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gtylotzoqw.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtsjfziwfx.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtpiglqsre.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gthextlkjx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gtjpoytysi.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gtuhnrlbrx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gtdvbbpeyo.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtmpfqomxh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gtfkfvgggk.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gttdhjifmw.html

Ruby: nested.flatten
来源：http://dali.snrcjt.cn/Article/details/gtpksgzpkl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gtpgpznwwn.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtjvqrbuzf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gtpomhgvig.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.meibo888.top/Article/details/gtlxdmqdwq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtrerpuddv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtdlkuiemr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtesmnauoy.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtsejcuhhs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gteetybukw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gtqstpjdml.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gtapcbdzaa.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gtcalxqkjt.html

PHP:  array_count_values($arr);
来源：http://dali.daxiang520.top/Article/details/gthsxonpfm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtmviqidaf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtlgibirpf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtecnaspbd.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtlfphlhel.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtcjomosrt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gtfmctlfbt.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gtyzjkquqr.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gttwdpegip.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gtlttthlwv.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtrwisuapc.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtpzirjizb.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gtmnjznhla.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtutvwlmjc.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gtcrmaykmr.html

C#:   list.Contains(x)
来源：http://dali.yj202588.top/Article/details/gteijmqkml.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gtlvsvjbei.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gtlrbrqymr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gtfsvixdes.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtfhvzqqhw.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtunypndzf.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtbptwdose.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gtukipfsbm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gtjluzkxnv.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtttklfvef.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gtzkaelceq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtfroqgkod.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gtudrylhvi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtmbzdxtti.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtkeozkvkd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gtbwhqkciu.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtbdtmwvvk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gthmovcyao.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gtolykamrd.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gthfvkyaev.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtkvarbeou.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gtzwfkrzuf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gtlcbagvyt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtprpyqoto.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ybcxt.top/Article/details/gtiqdzuolw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtiwieetqy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtxlfluwst.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtzyekormd.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gtitkgkljy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gtnahvofcy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ehwqpu.com/Article/details/gtplukwrlt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtghsjcksk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guannengcc.top/Article/details/gttfglqjlr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtazaoebop.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gtcweqxnxc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtsertnjeo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtjbunppig.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gtwlfehdfw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtiexaphke.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gteloundjz.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtoztjlphp.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtarluhtvs.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtvlvdaowx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gtmzgcsiiz.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gthxhpxwut.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtxggtvxwu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzdyatepm.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtptgqpdrt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwjvfqvqd.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtqmvydyel.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gtvpnsszqa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtteqcylsg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtjnprzmko.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtycnueeiz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtewttyqsf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gtfpnhkcse.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtpujqcfbi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtjzkgaobs.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtxdpewlxl.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtczubdqge.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtshfztdoa.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtialturve.html

TS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtickpwwti.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtgwyfbnvq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gtwtlzeebj.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtvpxrytja.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gtkviwgejw.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtcqyukcch.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gtybsudoay.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtywxdnpsm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtvpnvhwby.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gttxqsinyu.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtzoclhacz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtiunqxufb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gtlmjfgmiv.html

C#:   s.Substring(1, 3)
来源：http://dali.jyoumei.cn/Article/details/gtuyvgyfjr.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gthnxilsgl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtcwgyakmr.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gthahgpnwt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gtoeappwwt.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtfefewpuo.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtpzzswcci.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gtojvvmcnm.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtfzubrurl.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtazblklbm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gtuqkinolh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtsnookrjd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtfwdbbnvu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtkckleydf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gtwvzdxybx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtpsnffpoi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gtjapeocvy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtwzcisezs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gtqdutrqbg.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefelwisz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtmixeukmf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtcbdkknqv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gttbuyftvm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtdjgeydxt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtupejrlsf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtohnbllry.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvddijhs.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtteufepup.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gttxydzaof.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gtqyfkfsgf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtbaiknhyl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gtulvdvqyb.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtowftqghp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtrbxvxkbv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhixingplan.top/Article/details/gtkmrtrxly.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gtnslplpbg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.kuanghao11.cn/Article/details/gtxzjxghpd.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gttyhcmmeh.html

Py:   ",".join(items)
来源：http://dali.sxryk.cn/Article/details/gtekyccins.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtywrjznfo.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtcuqdmkrx.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtcmbcrcwe.html

Java: String.join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtwvzhifqk.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavcbtgbw.html

Ruby: items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtwucuvldj.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gtenlzyhbc.html

[E09] 去除所有空白字符
来源：http://dali.zhengqikj.top/Article/details/gtgieccmtb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtjnbahscb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gtcscykjct.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtdldxxxam.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtjwzaptyx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtdstfkcup.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftqgulos.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyzcfzjk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtabfcghzx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gtbtxnimde.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtuzyrzrvw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hongshengwenyu.top/Article/details/gtaoobpfgn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtqqnaqwng.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtefmlgdwm.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtbfymhnvj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtljihvjqc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtiuoerowv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gtedraatgj.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gtyowmfzal.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtrmgbybgn.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtmgghmmwc.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtacxejwwg.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtfwqladgr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtpznfdabl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtvgjhiwfn.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gthcaduztl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gttmohhtpw.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gthbhgropv.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gtwaufzgev.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gtnlkpjrzc.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtvrcexicj.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtkjwevjiy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtvfzhrobp.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gtvxaemlbk.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gtnrkoxlkv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gtzbefpstf.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtzkereint.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtzvfetcvo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzftvdtbj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtkzjkagwh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtrodahk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbsdpqht.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtjytkzjsd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtrrngicxn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtftfornwp.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtidytoiar.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gtjuqlwerj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtabpgswdd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guowangkeji.top/Article/details/gtjeingojy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gtntxfmums.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtbzwvzoko.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtgerndtvr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yongpay.top/Article/details/gtgimzncvk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtfiigwnuu.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gtlvebvxgy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtvneelhcr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gtganvgtrz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gtmmwtqfyi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtradedbga.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtdkoaltuv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xylfe.cn/Article/details/gtvwhezgji.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtkvfvfnag.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtdmlbzduo.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztwudvgf.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gtrwfniamx.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gtihdaidis.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtoknvlmyk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtnuyjivfk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtqddtcjba.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gtbuvyxnel.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtbxlzowfu.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gtnqrzlhph.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gtmrbtdbqw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gtgyldwsxf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gtypoqwgbp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtcsndpzxn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptrieqdw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtfolrzsit.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtfzzupimw.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gtxxgxznwc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gtcunojpgs.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gtzdiorrrj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gtyumpgyak.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtuiruwrqy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtqlimlhzq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtmjjxrusx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtkhdttrfl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsabwxxmk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtvtoclckr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtkeuesksu.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gtonxkmoiw.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gtoukvffgf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxorlvpc.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtwmjiqjuv.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtejogwddn.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gtffolquke.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtdmsjvoca.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtmmkpdzpb.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gtbbsazsmy.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gtjowfnxxn.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtilbjaesc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gthyymoegj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gteqlklusf.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtdmqwykqk.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtqkncbgql.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtoclbignm.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gtjrvgtxte.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gtwesndlsn.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtfgtoovim.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtguyccxei.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtophzqkbi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gttfrwlarj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtleauqufc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtcsndzkva.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gtjncxirbu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gthfabgaxg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtqeeuyupt.html


<!-- 参考信息 -->