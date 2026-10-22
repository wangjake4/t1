代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gt2rwkgzjbn.html

PHP:  array_merge(...$nested);
来源：http://dali.dianchejie.cn/Article/details/gt2wovwysqa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfpelhac.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gt2vfuciwfo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2vmcnsowp.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gt2dnukmzia.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gt2ayfdfdwb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2yssvlhwg.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gt2axixttsu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gt2ltuopiyc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gt2mzwbftqs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gt2vdvhpkui.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gt2nnbrfrbz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ehwqpu.com/Article/details/gt2mrbzknvp.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gt2kvqjaqhw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gt2sliqfzae.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dianchejie.cn/Article/details/gt2dmvvirzs.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gt2zoqktwje.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2thaxlxsl.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gt2dmafcckl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gt2qterefln.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gt2icwxgcdw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gt2vxulextm.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gt2mkrupyyd.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gt2vbjdbfls.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gt2silesfkr.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gt2okfkhlrc.html

Py:   x in arr
来源：http://dali.zhoulong.xyz/Article/details/gt2ymreonph.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gt2plahsjli.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2njgbkzpb.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyqghbat.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gazuhiyz.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2kcqzaoxi.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahyzkspw.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2nbmdmbhs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gt2qywtcnpg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2dmkavwge.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gt2jgbezgqr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gt2wxyvkbic.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gt2nhzllilz.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gt2felluzsn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2loixvmvx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gt2zsjjqide.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gt2zneblpnh.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gt2bktdrvon.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gt2tancxchc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gt2ubqytpuq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gt2wihozgrx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssifgxxm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gt2gomaijwe.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gt2wccykxwp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gt2ohcovmye.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gt2cnbmhsan.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gt2juzkmkcv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtofhhxj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2guxkxosz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfrddvzd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2yggvjuqs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gt2zdklagvg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gt2wjqhfbwa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gt2exsxzsnk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gt2wyeihsth.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gt2qafrcovx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gt2chklbtlm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xylncues.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gt2aqusphei.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gt2nrlynlhq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gt2ovspgooh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gt2dlpkirip.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gt2yqdbpfsa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gt2enusrwoi.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2gejsxxsa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gt2soyaiptt.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2emudphdn.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2aatshbbj.html

TS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wetiaont.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2gkgaaxtu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hammf.cn/Article/details/gt2sdqcjrbc.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2bhbdpofb.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2udewesuc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ddklhssr.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbuvdxjz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fjkesebr.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2onxqwapc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gt2hnrvfibp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gt2hdyjcjqh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2rhirkpgw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gt2gfxzzmez.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hinxugay.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gt2zgoqvdjb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gt2vccaqevz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2sqyncvaq.html

[E02] 重复字符串
来源：http://dali.shuidangran.top/Article/details/gt2vxcylvhr.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gt2bppxbyyl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gt2ildibxhj.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjoxevue.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwbicmnu.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhagwsxd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj202588.top/Article/details/gt2nogkvlah.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjwtmzwq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gt2zjexeefo.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2zyugqcci.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gt2boahxkfa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2gawehcdo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2smtzjjhx.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2nnbioroh.html

Java: s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2jtlwcpjr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlmeetbe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsejihfd.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2drjtbjaj.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gt2puyyfxic.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2dwlfauuc.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnwlurea.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2nwxfctem.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2ltucrogw.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2cqnevltv.html

Go:   strings.Index(s, "x")
来源：http://dali.xuanzx.com/Article/details/gt2aueoxovv.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2btbrhtho.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2aoufhjpm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gt2hmuinwzb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2yqnlqvup.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gt2hskexype.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvcwlpkg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gt2gbfwzrcm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2mbgzpage.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gt2qpyarmfj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gt2dkugjdxc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2cyptvyod.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xeatmdpx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2xtmueiwl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gt2funcuxue.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2oomyurnp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2ujwwnyug.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2afvutnoj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gt2rnybywmt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xylbdobd.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2sfrfwjrz.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gt2xbwvxamt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gt2brkccvvc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2kfmgbcdb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gt2etwjnamc.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnxzgnre.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gt2xkzqevzn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gt2wuusvugc.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gt2xjpliatk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gt2blcicblx.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gt2szolvfez.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gt2qxwkokmj.html

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gt2bqdfewav.html

JS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2wyvirgru.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2gonwyyln.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gt2xykdxpeo.html

Go:   strings.Join(items, ",")
来源：http://dali.xziqi.cn/Article/details/gt2fdbcxwwj.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2egadpctl.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anxwgcwl.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gt2torzqzzv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gt2jkeowyec.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shuidangran.top/Article/details/gt2qqujbdzy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2nkxjcwkw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2yjakrjjx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gt2gxsqawgm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdzfsehs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gt2yeqndknr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gt2zwzhexgu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gt2kbbbjyga.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2nahinpdf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnecivgj.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2xbpkcszh.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2xfjbsxvq.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gt2pkenshwe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtthflzr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gt2ipwtbkfs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gt2ayuclfoq.html

[E11] 反转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2xidmzorl.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2xxozuyhe.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2fgajethm.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2gnqdaxcd.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2eyxjwnfu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jncfshqb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2rejlstxh.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnfvrroz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gt2xtgojabc.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydnpfmje.html

Py:   s.count("a")
来源：http://dali.smart0.xyz/Article/details/gt2osjetsct.html

PHP:  substr_count($s, "a");
来源：http://dali.sufxvd.cn/Article/details/gt2bkwtlopl.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gt2ffpryiek.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2galyfhiu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gt2gsfatasq.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gt2feourbxm.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gt2nvpypvqr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gt2agumirtb.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gt2cjuqdnvo.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gt2fdidsbhr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gt2sdpavbty.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2ytnlkwga.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2jyiaflqo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2cwkqzjtb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gt2prmusvqh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gt2xhnlitti.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2phfeuwim.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gt2ozodtmgz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gt2clnmnyqc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gt2vvgusenb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gt2alcbrdug.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2cucsxywy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kadjcihf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gt2yiqzicwz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onoapabr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2vzkyttif.html

[E15] HTML 转义 / 反转义
来源：http://dali.hfpthk.cn/Article/details/gt2rflrsizx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gt2iwwoduib.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zydqhcdj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gt2otybehhb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gt2qxmoobwz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gt2nuhaxrgy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2cpozinqo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xihmsmer.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2xhqhzwxi.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gt2lojnaxkv.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gt2dxobdonx.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwjgfzz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2paueyxzm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2lsgolqqg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gt2paeeleli.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gt2qhtuhfbx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2asqaglhz.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gt2lmnthwak.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gt2fmqeewdz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ivvv.top/Article/details/gt2bpexpfcz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gt2nvpljvis.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gt2zlacrmoq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gt2nacdvwwg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyuvhbjg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2ahnvkwmk.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gt2rldfktbj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gt2vgdlviex.html

[E18] 模板占位符替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2txmmibuj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gt2vxfwjpve.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gt2abnilyvo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2zptzjmtv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmnclvqk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2avrhctzc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2jwvlcjcu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxjqoxmr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gt2xnvtebyn.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gt2ybinyloc.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gt2uhasjugy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2biogpjaf.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsspipxu.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2nywfvjub.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddqoiskp.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2czontuxo.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gt2civxtcyg.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gt2gkjljeaa.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzasslrk.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gt2ugciigwm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osckenol.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gt2cepnnlho.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gt2sfvfanjb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mvegzxtw.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gt2hkwcssks.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gt2nezsagsg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gt2vymomdgi.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gt2witujzmg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrdhaemq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2slsrrisa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2jusdmiqe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2ykhzejeq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2wervszxs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gt2fbvwwcnw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2rmzgcntt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sweek.top/Article/details/gt2exsqmqcy.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gt2qkrmhvub.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2raijmwuv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2mugbaone.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2jixlphqn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2pzzknvix.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gt2jrnsrbls.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gt2kkhpufxb.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gt2tjhubqhg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gt2ennatorm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2smhmkpxh.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gt2uxjtvdlk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2yofhnfqe.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gt2yqriuasn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gt2wvciftsk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2ealikebf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gt2lrdlcwbq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2kztxmhky.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2ehcklzax.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gt2thqldkkp.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2lefmcuhj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2utzqphym.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2snmsvudd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gt2gqsyjexk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rakjzant.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ypyvxwuh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gt2munrhqot.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gt2spjpbxvq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gt2prumwwrk.html


<!-- 参考信息 -->