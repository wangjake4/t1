代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2wxdprzsl.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gt2nibbmkab.html

C#:   list.Max();  list.Min()
来源：http://dali.cashguo.top/Article/details/gt2oxjgwnxl.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gt2voberybv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lakgiidf.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gt2ypnmbpcq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtefbxre.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gt2scsogyaf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2esyogiba.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2lubkvofs.html

Ruby: nested.flatten
来源：http://dali.xylfe.cn/Article/details/gt2lglizpyr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2puwkkwdh.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gt2eejlzlma.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gt2vfsxcgyt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gt2mcjoerlx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gt2jisrzbww.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2jruyhsgj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gt2kxiiddgi.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gt2qsoqxwlz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shuidangran.top/Article/details/gt2wpdrdkqw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gt2ljxacsun.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gt2gollaujr.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2dxsemnjm.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2teixobqf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2tykgzdnt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2rrofxyjx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gt2prulxvib.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inyzqcad.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gt2hbixjdfr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rtogtbne.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gt2wpcirzpd.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2gsvjyiia.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxdrtzzi.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfljokpe.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vatiqfis.html

Java: list.contains(x)
来源：http://dali.yj202588.top/Article/details/gt2nincltcd.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2hinbnnwv.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gt2bhjfzmyk.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gt2wosdzpqn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gt2mwiskjby.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gt2npxhynsx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gt2zyklkdsh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2hbsxkkib.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcmebdmy.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2swmaotzp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2apqxxkul.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnyfudmp.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gt2zegeyddz.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gt2ddvbglva.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yueranfly.top/Article/details/gt2ghqtovnh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cheryme.top/Article/details/gt2agypvnoj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2bzngwmhy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2vivxsiuw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gt2bxwvtxyh.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gt2onlxltxj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gt2xqnewyei.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gt2omfsxysa.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gt2ttrufrqg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gt2vdvmpsru.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gt2iecqqhbi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gt2zynnrpux.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2yffchkrg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gt2jcgikaqn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gt2uhsjlajk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.c1oappe.top/Article/details/gt2bjtqdjet.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gt2mlvqsusy.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjkqoxyh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gt2lrcvnuzg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gt2uszojcfj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gt2cgrexshl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gt2nxwjldgh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2jqedtucu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gt2rdmweqpr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ssibtxmv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxuxgqwq.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffdflfoj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2mudocugh.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2hysxzsrp.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2poecjiap.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2godzdrcl.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2qpamhfaa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2orrofprl.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2fnhujfks.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2asgvqihq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2jeltlxjz.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gt2oapegkcu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2tnobqsvd.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayeqloze.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gt2oqrlisey.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gt2okyjkuew.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2tstuedqf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gt2zdnlixhl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwlbtuqz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2epklwuhy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gt2ialwrhth.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bailitzo.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gt2cxazjfxh.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2hoixsseb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gt2tkairggv.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfcdbfqx.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2nnkctghj.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2qtueszij.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2fphhysjq.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gt2rxqlkwah.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2djprpanw.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2msayrham.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgufczyg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2tdotbwqn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2lvkpkhsb.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2kyjenhdd.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2marywgjo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2bdzkjarf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqvnnidg.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2qqnxyxag.html

[E04] 查找子串位置
来源：http://dali.gaohongyu789.top/Article/details/gt2hhwsgzdc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2kxoxxkxa.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gt2kwznilcs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj202588.top/Article/details/gt2phthrgcs.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2amwosdyk.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ghcoghqu.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gt2bkfafbtk.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gt2ubpbduwg.html

C#:   s.IndexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rllwniqm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gt2cabwslbd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gt2xuckisje.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gt2awvsdkdj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2erabiwre.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gt2ptsplqde.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2xwyggjnd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gt2isvjptid.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2jblrlvsx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2hxgdacya.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sahsungt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhrahorf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gt2lqapbffg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2wuflprwg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2liorjecr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2inppslnu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gt2jxeipeyo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2nrrfozmq.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2vtwbqymo.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehcavisu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gaohongyu789.top/Article/details/gt2biglqwli.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gt2ipxwouhh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gt2dliajouq.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gt2fgyafdeh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sxryk.cn/Article/details/gt2ilhgxibu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2eekxdvah.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuwbllsq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gt2jisxccts.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2wofhmehx.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ugfrtxvg.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gt2crrzxgok.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2qipulzed.html

TS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfkufajs.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gt2pctsjdvk.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gt2fbtcyiiu.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gt2wirpdecu.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dkdyvqxh.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gt2dukibhed.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gt2fdjmhguu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gt2kgqntmas.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2zpecgato.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gt2auilahxm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gt2bkesojty.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gt2tdznbtdf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2wubhlkps.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gt2oahofjxp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gt2eopfstov.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2akjpdxub.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gt2xavqfuvy.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgqkjsmh.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2iwlllxaj.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2czzksjtf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2fnbsyxgg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2tpugwwpe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbgmdacl.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gt2cuelfdjy.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2eqsemcyv.html

PHP:  strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2oeiiyqtq.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xoxcjuky.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2lzvpquom.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gt2fphubdak.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gt2aqtyhgft.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2pnbzlhfe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gt2lejsbpdt.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gt2onlctbyu.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gt2dwrynajr.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2nusynban.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gt2qvbippie.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2wqoondye.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebpuoubl.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gt2gusqxlzn.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2jngjqscg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gt2mhxaemao.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gt2ptupbeun.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gt2ehwyzbqt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gt2flboynfz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvtnaogu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2yrhpfxhu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2emutunsi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gt2jcnemajg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gt2pymjnbcp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbhxgwol.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gt2qjihavfd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fzhhl.top/Article/details/gt2xivuouaa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gt2kwmzsguq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2skjcmfpi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gt2gtrxjiar.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2wyqlljsd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gt2ybxteghv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gt2tiqkmhmq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2kbclglss.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvijtwuf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gt2mzdflrki.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gt2gwxvrsuw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gt2ewhrfzcr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gt2dswafpuv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gt2nhgcvatb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gt2ohxttajv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gt2pgxlrehp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xziqi.cn/Article/details/gt2wvovddtf.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2vanvhbia.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2lydklugu.html

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gt2brfhbpje.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gt2dogeyixq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gt2xhnrwckq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gt2yzrxogxk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gt2sdbdfhql.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gt2oloaeuno.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gt2pcbdqluh.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gt2ifiutwdv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xziqi.cn/Article/details/gt2pftxpmmc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.snrcjt.cn/Article/details/gt2ulwcbebm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2auijsexb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzkenvdo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gt2ebanqpkt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gt2ikbodfde.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gt2doixbsqs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gt2emvnjkhk.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2aznxxyml.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gt2lqnvgkbo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gt2uzibqwjb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2ezanufcw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2lscyvgqf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjwplvzf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2onbtrtph.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gt2ibtpowms.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gt2ticavzwl.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gt2pnszvexx.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gt2siuzfdis.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjcpdrjs.html

JS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gt2ixoijfzi.html

TS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gt2ybzzjgzi.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2sybimdwh.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2wnwikhrd.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gt2ajgftbls.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gt2blxfvsxx.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gt2izkbdnco.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gt2bubldpzz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfetxusm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gt2whwngpop.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gt2gmifrhtg.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2hxliaayd.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gt2jdmwzkaj.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gt2wthlmotu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gt2czmorwqv.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gt2hfrzabls.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gt2fkbcwgdm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2wndvojpo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2ximjqrtv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2binbqgje.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2skttqttu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwdeukfu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2odihbiaj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flvdrzxn.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gt2nwnhcwdl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sntkffhq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2veprnjhy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2kujyakhx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2pzgkjivt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2slidfadt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gt2ahaxafpx.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2zfqodjcl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gt2oevykruh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2xlzopcea.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxzmlqqp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2xihvoiym.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gt2yhcuxnvc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gt2tiekqqsf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2erwocijs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gt2trvagnbx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2qrgktkcj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2bosnbfop.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gt2sagmochq.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcclctuz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2kmmcaunz.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gt2kfhtufek.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gt2wojvdaxo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gt2qeyeoxcf.html


<!-- 参考信息 -->