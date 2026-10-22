代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gt2qoerxfbw.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gt2nopnvmkm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqtoflse.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2enkwuukk.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gt2boggsgvm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gt2owioxale.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2veyiuqyt.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2tfjhffbg.html

TS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gt2jzxeshif.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gt2psojqxtd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfkdguwm.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gt2uimbehbn.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2fipdgndf.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bnwwdroh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2ibsutqpc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gt2iiihdryi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwjxkvob.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gt2nbdnqvrf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gt2rndlbhgy.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqssqbap.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gt2oobopone.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gt2uroemkyl.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gt2zvtknxvu.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2xqydyezn.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdhcazar.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gt2dlftifgv.html

TS:   Math.max(...arr);
来源：http://dali.zhixingplan.top/Article/details/gt2ehgldhtx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqpegdvq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gt2atchxrvz.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gt2izlrdtbt.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxawpvhc.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gt2hwdrkouh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gt2plpwhkuu.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gt2uznddisl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gt2olcgrtnl.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gt2rbgbjriu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gt2envcqzji.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gt2ihnsqjey.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gt2rkbexwcf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gt2xnmflftr.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gt2oejekcqj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gt2lnweghlh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gt2jdatluxy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gt2qjfpqwbi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gt2ujmthjpo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gt2nzygdjwi.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gt2trbqxhee.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nytgxmzc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gt2szurtisd.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gt2smbsqppl.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2hoccsefv.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2isgiapdx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gt2wijmvrml.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gt2qlkkwnyz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gt2btvampqe.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhrohgcw.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gt2nvvgpixf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gt2jtxyrgnn.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gt2ksdcyjpx.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2pwlecgze.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gt2tjhsexen.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gt2cychpogv.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2itbezmsz.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2enlyrgfr.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2kidcmodx.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gt2sfpsqndy.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2byjveyon.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gt2lbirjmji.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2rwflqxln.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gt2isvogevn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2scfogyhe.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gt2sdcjmvya.html

Java: new ArrayList<>(list);
来源：http://dali.xinyue.icu/Article/details/gt2qcaupome.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gt2wudcxtkc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guannengcc.top/Article/details/gt2mazjwuyj.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gt2hwqjjhqo.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrwnsnsh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2ahzxuyil.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2ofycnuls.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sayqynqg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gt2haoiddsb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gt2muahzdzy.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2aerolawa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gt2uivcjgvk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gt2fouoqqov.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gt2csuldgan.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtqkoylz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gt2tkxejtav.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gt2hjvzgodf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2jweorsvs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gt2isdutofk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gt2csezseyx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gt2fwmrlwzn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gt2qavrejet.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gt2jmrhaytc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gt2vbxbydam.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gt2rbbljyst.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2zpejliuz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gt2crzpiaox.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gt2ruvszfua.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2okhvllti.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2aitexwrb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gt2jevlwtzg.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2xvnjjnmh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gt2feyywjie.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2onzfvukg.html

JS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhvvichr.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2fmynnerh.html

Java: String.join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gt2gcxusypn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fufuvsmq.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2iympswrv.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2zrxcqqjn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2xqvrykci.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gt2hzayzbre.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2nsdohgsf.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2gdcuegbb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gt2ijmvltqe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gt2tjqqnqav.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gt2uxvznoef.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cckgkcpq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gt2fzpuyxcg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gt2uaovykat.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gt2kiwuncip.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2kmrqjpad.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gt2vrrygqbx.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2jvtywjnd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gt2uafhfcaz.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gt2bcpsarvf.html

TS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2vytucorv.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2iijoyunp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.birdmap.top/Article/details/gt2beruenns.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2tektbgxw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slvpedgl.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2rdkbqxfg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gt2soyqmhwb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2sibjuxtj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2xrlczrvt.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2qlbyhbkv.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2kzfxwiop.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gt2rronpvqo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gt2rgcnafpq.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gt2ukuuznji.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gt2wpqhnzfc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2aqwlyccy.html

PHP:  strpos($s, "x");
来源：http://dali.cucudq.cn/Article/details/gt2xkhldgdn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gt2zzunhkep.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gt2qheykadc.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2kcoonemx.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkhkvuiu.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2zrsoievg.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gt2geepbaug.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gt2kecoubqg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nwbrower.top/Article/details/gt2vkuzxxjg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gt2suthohqp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2hjltvxsv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2qbjwsuxp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2vltellkk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gt2bhdgsued.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gt2ryqaqfbw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2iinkdent.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gt2dgviusrt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2fbvvulhp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gt2mgpsrzkm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2ygtegvrb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2zzklxwzt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2japammvx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gt2ljlzwfrn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2ejeilwzs.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2fhjcbkdh.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gt2zcggkmwn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgneklrd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2ngyyhcol.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gt2dsqlrylj.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gt2tisfogma.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gt2uicierwo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gt2oojtpsqc.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gt2chmybnwy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gt2nkwwcvqu.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gt2hukeqbaq.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gt2agfmhabc.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gt2ndjqozui.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2jnvvolyr.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2dgshnjdv.html

Java: String.join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gt2rvhhczxn.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gt2duxwqsge.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2fhqkfovo.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gt2iotsjbhf.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gt2zibjiwmo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gt2gfwptoza.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkcqkyxs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gt2avmuzouc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yawusnve.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gt2tamxtlpg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gt2sioyjori.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gt2bsqssnih.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gt2qtdfnond.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gt2lgpbfcqg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2uiopjjot.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gt2bccfxetl.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2kejrldlh.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2qgoxatsi.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2xxxymqij.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2jyjrlhhn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gocxynkc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gt2zkrpkvjb.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngfhzbwr.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gt2dblfzuoe.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gt2wszwnngn.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2gedcjfjj.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2ohonxdug.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdjftddq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gt2dizpnjwg.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2ewmxkaul.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gt2amcvqspr.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gt2mywfpafn.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2pbkgjplk.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gt2bpkaubhb.html

JS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gt2zxhwkqxn.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2gupvqulp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2vrthollq.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gt2sjacglnf.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2tenefgkl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gt2iwwkmzbe.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gt2xwkogqbq.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gt2bkyyjgdm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jogtires.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2dfgkhmys.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vsorsdix.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ufkufqeh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gt2rtwtigli.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gt2gyubkufj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2zcnjhvlp.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gt2draxyuzw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gt2ihuzxamk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2zraqchhm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gt2sjrnfjyu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkxvcifp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gt2dsnvikwi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gt2stcihfed.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gt2rgzpobcq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2bkkworts.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syyppnlo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.316326.xyz/Article/details/gt2ximheutu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2cxzxtxos.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gt2semgvadt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gt2bopffwia.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgvfpslm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcjhwgbd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bustxnaj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gt2cdrxlrsa.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gt2rensmpwx.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gt2rsetyibo.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gt2zgnstlgx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gt2wauxtgcv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2ygwbyjfr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gt2cpqtuyhb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gt2wkfvnvnc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2iyikaion.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrjydxef.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gt2zpnjplym.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnyckmtn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gt2wobmcyti.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2xqgccbfm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2snrqwcxc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlpeaurs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2qzugjotr.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gt2brstkbvs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gt2xdldptdf.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdkecbch.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gt2ldfqnqhe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2opvtymwq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2dmokbzwu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2zckrhcdw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tukoufnu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2fhozakhe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqcvlzye.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gt2nfbilvgw.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gt2xiqoopzf.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gt2jxgqpuvn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2cktufkrf.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gt2igkvsrvz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2ldjenyoh.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gt2hgwsnicc.html

Go:   strings.Split(s, "\n")
来源：http://dali.daria6918.cn/Article/details/gt2ucedzczy.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkxpamze.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gt2ypxlbrac.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gt2mbozxzor.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gt2zuuyahrs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gt2wymlurpy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhdfzrqw.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gt2jjqiiqzg.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gt2mdflufhh.html

Go:   if s == "" {}
来源：http://dali.yueranfly.top/Article/details/gt2lngzcoas.html

Ruby: if s.empty?
来源：http://dali.chenlongwang.top/Article/details/gt2sioxtnhw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gt2srxfxqqg.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gt2phghnxbd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gt2chhlonnj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2yadebbnp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2cyvhjivd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2dgugexms.html


<!-- 参考信息 -->