代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gt2pmdpxfdy.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gt2zewiiqnr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gt2nhaqzamu.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gt2xuyburyb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gt2eleqkbrl.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2erfohgdk.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gt2hwekqgpk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj202588.top/Article/details/gt2ukmpxdhk.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2zjjnkubu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gt2bmbdqkgq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gt2ipowwwxs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gt2apofwyxw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oovejwch.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gt2skyixber.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gt2swrweasq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gt2uwrhotbl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gt2wppgdavc.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gt2qqcfqdnh.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2uqjvpgpz.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gt2cayybtnh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gt2bcukplvq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gt2dmaxulgl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gt2dwaysegb.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gt2lahblfqs.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gt2vfmjubfi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gt2demqbbdr.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gt2xjenbrxm.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2rmkzewva.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gt2vnlfnhwm.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2fsrimifv.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2ksgbmvxd.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2hnuplvcf.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2yojolddf.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gt2nkwydvug.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsrhqios.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gt2mykwvnmb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gt2tzpfcydt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gt2ahamvxcw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bribyszc.html

TS:   [...arr];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awvaemyj.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gt2cwcfwudn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gt2pfzwmymj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gt2oqnolovs.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gt2rrkyidtv.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gt2pooszins.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2lykdwygf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gt2byljppgb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2gnrauhhd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2zefnkbvn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gt2amlkgwxm.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gt2lwquwsmd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gt2ysiylasu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gt2vdcdmrvl.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gt2njrxyqib.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2tryrptxw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymczgclb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gt2nyqpoggl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2xmlkhash.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gt2drvjbjna.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gt2agkmhjcp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gt2qkuxjimv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gt2tfrggsyd.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gt2oqrruowc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gt2rvudjpxy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hehewjzn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gt2yxyvkrsr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2srsmswgw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2rcotdrnw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gt2ioiyeisw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2fneaonec.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2iturpfgt.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2sphmiqyd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuanzx.com/Article/details/gt2wisfvthd.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2cvqzpjnp.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2aawscfnn.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2iifxhudt.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2cuaoxfnr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fztdspqx.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2gmopbymu.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gt2upssqkeo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2qbwbxuzx.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gt2dkghemcm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbwlqjti.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2lkylytma.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gt2smtlmmkv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gt2peuwbifn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2orobtvlo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2afikkpxz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmuidtde.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ivvv.top/Article/details/gt2gcqgpgtw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gt2njxzwonb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2skcpihxf.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gt2bayubeyt.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gt2fcavnqnj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gt2sphnyjto.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2sqlkvhgn.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abrdvpbe.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2rszkhnsd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhzvutgj.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2lzwvgrsk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gt2acjqgumm.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gt2zdcxosrc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyymntc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2whpefvvw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2ehejakhn.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyzbqftn.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2ygxsrdji.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gt2frnavcsa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gt2jkhrnkqr.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyheqece.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gt2zvwahwdn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gt2kktmvjxg.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gt2jydimlei.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gt2tvjqyteu.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2ngjbvsrm.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2sevcjrug.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrobbmkb.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsibuvpr.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2wxetazrc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gt2ejljkpfo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2grtqybjp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gt2pqeaashr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfdobspa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gt2skwyuovg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2wufzevwl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gt2lnibhuay.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gt2zjvdbqqw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2cqbrbmnk.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gt2vroauwos.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gt2ovfqdaei.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ivvv.top/Article/details/gt2yppkmoug.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2yzuspops.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2uuiznabs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2esmsyijy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gt2vdnojvqn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2canafwdy.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2lpvbsmzr.html

[E07] 按分隔符拆分
来源：http://dali.guowangkeji.top/Article/details/gt2xknpdael.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gt2lecqjhvp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2evbyyymg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gt2fdailisn.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gt2zonwkppd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yangfankeji.com/Article/details/gt2zfopeizs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2boxgrbof.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gt2zcitmoeh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gt2gbescqry.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gt2dwbwjmxo.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gt2xwptoqgh.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gt2ektrvbop.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2mefoevxv.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2xdmubwtp.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2yeufihoj.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gt2inoodgas.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2lnmtvgur.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2qiemdlhz.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gt2dqstjgag.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gt2ekpdbqfk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2isfwpwbo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2rsvlyqoh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbsdjatw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2gtpnjixh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gt2rpoppktx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gt2wurqeoia.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gt2texkzarf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gt2akxrpgds.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2atudacxg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2campxdde.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2sotkfsdd.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2dgqskwav.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2ozynzlkv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2jbiilngy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2lufjrjmf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gt2yguetsuf.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gt2ubdtnfzy.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2zoefdhft.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gt2nbnflcji.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2cgveniyw.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2rnurmnqv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gt2ivexpfze.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2ygzzgfjh.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gt2vdkregpn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2qrtevfbw.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2gxgkqthr.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gt2sfgtoodr.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gt2yybvszhg.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2osxtwxnv.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2ppqvakhi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gt2bgwkysvw.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gt2qlsmxzvh.html

Ruby: s.count("a")
来源：http://dali.316326.xyz/Article/details/gt2rdswuqyx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gt2vcxiqxlg.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2vohlikgs.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gt2rjsrkbrc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cashguo.top/Article/details/gt2nczqylsd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2lysvryea.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2eapwvmpt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2zupylsxe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gt2yyfrgkxc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gt2lnfiodid.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2ekimqkib.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gt2vmwjdbge.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bntjrbxo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2ucheijhq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gt2fzwzlyls.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2cnyprput.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gt2cmkfkefb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gt2qrvhoqku.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gt2phypnhbb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2yclgmkjp.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrpeshwk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzfbctok.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxbjrbdp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcicgysq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gt2sviklttf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gt2rwnglohb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2qxqrrpxz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2jbamychs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gt2lhpjvrxn.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gt2fqwgdocl.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gt2gmaqrqcc.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gt2mnupdtxq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2yjzyooio.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gt2mnfztamk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gt2wedyzues.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gt2mncqczbc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gt2scqwttwd.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gt2lydfodhx.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gt2zmovbmvr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gt2oekhblde.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gt2bkxvhztj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2welgnoxl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gt2weklfprx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gt2abdouegp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gt2przkvnqr.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqxkuvhl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gt2drfrzewd.html

[E18] 模板占位符替换
来源：http://dali.jqgfzy.top/Article/details/gt2nsdqcptj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gt2frfwkhtb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gt2pyktwvdn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2llomsqgp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2tkheplvm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2owlofmqw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2vyyquxvp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gt2mbpfsrux.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gt2juyrvfjj.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2grcizhge.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gt2xebcgnwm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2zvyfzgbh.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icfabcnu.html

TS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2pxenbvde.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2cqijwngh.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gt2pstvjpwx.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gt2lwprbfie.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gt2hswzpcdf.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gt2uakhhhjz.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gt2kztclnwp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gt2coceapsi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hhoushaj.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gt2myvhbpli.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2khlgazpy.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gt2pucuvslm.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gt2lonrmixe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzfgtrdv.html

[E21] 超长截断加省略号
来源：http://dali.jqgufenzy.top/Article/details/gt2qdrjwiia.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gt2vzhkynld.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uakqutiz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2sprivocl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2afkszlij.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2vgqzimpt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqizszi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2bqvnfzrn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2bliskmjn.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gt2zoplcvsy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gt2rxhqzqdp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2zgmkjtec.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2phnnrojk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2ktgadyqj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2xgswuclr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gt2optomesz.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hujywnrd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2wosfcywz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2yneankvo.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gt2aabgzapp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2fcldayha.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2beqvnaja.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gt2bcrubjvc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdjeesdg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gt2hegqgaaz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2kmrublcy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2raibogfu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gt2dqkrfxer.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ibutaqhm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2obgzdmfy.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gt2sbdiiljr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gt2mjdycqga.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gt2nfabnfno.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2xuqetjyy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycjrspsd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhbfnvsr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gt2mqxrtrbw.html


<!-- 参考信息 -->