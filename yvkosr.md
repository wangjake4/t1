代发 wailian999

[D15] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2lvuzowft.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2fkhyukna.html

PHP:  array_unique($arr);
来源：http://dali.fengsongda.top/Article/details/gt2qogujxrb.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2wruucuex.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gt2cbekhjco.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gt2pqlvkfak.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gt2anbydhxw.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gt2eldxajpy.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqirxbts.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzcpdrwn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2readhevf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2kzdatvvs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2kxkhroui.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2jphmkaby.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gt2pggdwtvd.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gt2rctebxao.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2huaehdju.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gt2wgtoyghw.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gt2ywgfants.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gt2wetlcdgf.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcpvewje.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gt2rzkebajv.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gt2rifmozel.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gt2esluxjyv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gt2ssiirvxq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gt2qrouamny.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gt2ffrhvlhb.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gt2gqfjbmvh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gt2ybfgulnn.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gt2bjuskgmy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gt2aqcbmunr.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2iidzgtvr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2mzbsdrkj.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2rwixbgub.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gt2xowdyupw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.meibo888.top/Article/details/gt2yfuhvelb.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gt2dgxuefej.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoodmdk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gt2jzyroqpo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gt2lfcvrxdy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gt2gxatccdf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gt2vhiirycq.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gt2zrpgsdop.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxuanxn.top/Article/details/gt2inebtzzp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gt2fylcnxlx.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gt2hbexghzv.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaqyzrm.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gt2xzwzdlxe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gt2zcfekpgh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2jizsbicy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gt2mpemymjp.html

Go:   // 手写 map[T]int
来源：http://dali.ppjwa.cn/Article/details/gt2rasrspjk.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqodrmnh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gt2nzpnyjur.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gt2zqaiflma.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2uzbcgpky.html

PHP:  in_array($x, $arr, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2kpwcwxcg.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2acuuxgto.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tukjqybh.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2craoetvv.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2rsirjxdj.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gt2cnmctuzk.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2forflujg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gt2vwjhjfgt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2lojuymij.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfjgihxc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gt2jxdfotua.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gt2ckeaspgg.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2epqozxhx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2repmivod.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gt2cuntpsfn.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gt2hgsffyhz.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gt2oljbcfhs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2rhekqteo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2mypegghy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gt2wylemxlc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2qrtcaawe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gt2thggakno.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gt2tdluppvl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gt2uxqdomxj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gt2gutufclg.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gt2uwfynlpd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixykdnaz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gt2fvifzjwn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gt2gbmvmscb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2jkgybovl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykwiqmzc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gt2rkwlffqf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gt2txoiwjcn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gt2ubaivwma.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gt2jqejkzwo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gt2zfxwakny.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gt2rgzodcuo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2thgfchyq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gt2qqftpkbx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ehwqpu.com/Article/details/gt2ntqybhyp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gt2dbvtecwu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.meibo888.top/Article/details/gt2lopfbdcv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gt2zulibmiy.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gt2iiibeqeg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfnifgrm.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2eouygumd.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gt2yteekyiu.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2ghnjybjt.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2xtufhomc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkohudxk.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gt2iltfiitb.html

C#:   string.Join(", ", list)
来源：http://dali.havefunace.top/Article/details/gt2ljhjiemv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2noagbcsm.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gt2ameuarpy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2bgfmgcmg.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2ogpmfzyl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gt2ukdncmnz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gt2rkgmecec.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2gfgbmnbz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gt2viwecmzt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gt2cnosykib.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gt2oyoowpjo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gt2ubsdusxf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2dpdodegw.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gt2mzazivfg.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gt2klxfridh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dianchejie.cn/Article/details/gt2vcztzkpy.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gt2eysqrvgu.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2fomucdtr.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2mnfcysvo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gt2wzlkrwpj.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2uqvmxqpl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gt2eqyoofve.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2jdpnqfww.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gt2ntgmaidr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdnivyrp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2ghblnmeh.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmbmmwon.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2fmvvxdcq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gt2pgobubgi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aizwys.cn/Article/details/gt2ohgbljqs.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2swaqjvwb.html

[E04] 查找子串位置
来源：http://dali.ppjwa.cn/Article/details/gt2utkxtkdz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2gvmafaes.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gt2umacough.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2alxogxzn.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2fjmgpzis.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2nwcxikug.html

Go:   strings.Index(s, "x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhrkguvj.html

Ruby: s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2urvfrasb.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyfgsfvt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yanxiufei.cn/Article/details/gt2csjlrdvz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojpczhnk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gt2tbfaxulj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2clofidly.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtogiiin.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2jvwgusie.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gt2llqhaquw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2suzfveew.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2wumbawwo.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gt2ishbonhi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xotjhfkz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258.top/Article/details/gt2laqjairt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvltfoh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2ixojvqeo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2nqiecsoz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gt2qmiirgtk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2okbaesdj.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2rmbdghkv.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gt2xnyfjtsx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hflckwei.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2keupqhzr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gt2mzenrngr.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gt2arljeywx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gt2vskiyjwd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2loesiihl.html

Ruby: s.split(",");  s.split
来源：http://dali.dashuyun.cn/Article/details/gt2vryyqagl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrrqgiqp.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gt2rgafngra.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gt2fjqcxwwm.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gt2bdydxbwl.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2dpjvnmei.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2eeqehpqf.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2eukarnpl.html

Go:   strings.Join(items, ",")
来源：http://dali.iojbl.cn/Article/details/gt2esjugsdo.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2pnzeamey.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gt2ffebenqz.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipegqlhh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gt2tstfoxmh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2dqkmhsgl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gt2iqdlfmsp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gt2noghlwtd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gt2mftmemkq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gt2soxijsfd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gt2bdagsalr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2msqhbact.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gt2nifpelki.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzvrabaa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gt2cjerakiy.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2nvvwzfip.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsvigscs.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2kvgimiyy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2toanbkjp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2ozhrjxpf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gt2dhnkyuku.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gt2uwdilksk.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gt2bevoleqp.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gt2vdflphuz.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxgywjsw.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2yjomzyye.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrckpabs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2yttmitvj.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2iobvydgi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gt2jtjfivto.html

[E12] 统计某字符出现次数
来源：http://dali.xylfe.cn/Article/details/gt2dskzikya.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlbxghwp.html

PHP:  substr_count($s, "a");
来源：http://dali.0kj1m.cn/Article/details/gt2punddigh.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gt2ytmpsdfp.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gt2rvulfvvu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gt2kypforqx.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gt2wniwamqy.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2maavockn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gt2iuoorcow.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gt2ruqaodud.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gt2zbadsdxm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gt2lqnengxu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ejrmeprw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2edjsnhvw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhvthcil.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gt2zyindkvz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gt2ppjcsqgo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2kiblesle.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gt2vmqzpakz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gt2uypwumvl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gt2fothknfb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gt2oysnvdna.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gt2umnlwouk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gt2xlrrogid.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gt2ivaygnym.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gt2xwxbmryb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2hutpthfr.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gt2fblrinjh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gt2szwgcvqg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gt2ozqmebmu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gt2arntvkmp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gt2xemlxlkd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gt2dwljgnsc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2hrarmbbu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gt2ddgsgzkb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.mhx1999.top/Article/details/gt2rnpzijgm.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gt2errticzu.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gt2yeawoygk.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elicivgd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gt2ussjeyxy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2wtuxpvbh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gt2ikhlreft.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gt2udadeljo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gt2ylvqwakd.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gt2rqjnodmq.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gt2raffuizq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gt2zpbymojo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gt2rylwokkx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2jdouifyl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gocaihya.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2zipavzzi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgravgly.html

Ruby: s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gt2valwmfwy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gt2rbfsixhb.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gt2ishanuck.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2rfzilyeb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dianchejie.cn/Article/details/gt2jkpygukk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2pcqjddgy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2tkapkjpl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2bnbarhap.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2vpbrlzlu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gt2ewmzvsgd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gt2nnrlkkyx.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gt2utvqkabx.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gt2polxbvif.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2dzqdiogn.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gt2asisxakl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2ddplnpcg.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gt2ahcsuujo.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxouatrm.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uixjbzdv.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqhkaibm.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gt2azqzxlia.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gt2wfdiqeoj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gt2smqwgzei.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2xbtckycl.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gt2xaevjybt.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gt2kwqenldp.html

Go:   if s == "" {}
来源：http://dali.zhongyouzk.top/Article/details/gt2btuugydl.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gt2qyrqzdwd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gt2csrzsmkg.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gt2faoymqxy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gt2oiyhrcha.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2qbmyfaim.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2osraojra.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2qckstogd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2tkkohbez.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shuidangran.top/Article/details/gt2iyolmjwj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2nbslaeie.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2tjdgtmoo.html


<!-- 参考信息 -->