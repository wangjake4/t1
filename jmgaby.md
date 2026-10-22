代发 wailian999

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2ruhyfgrp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gt2shdsdyxq.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2ylrmowvt.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2ddcpelch.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2gnysaybo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gt2jiujscae.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gt2wtwdyqry.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gt2nssicglu.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gt2veimlkkl.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdrgvink.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2coddrnwt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gt2cvcafqtf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2pokkdvwm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2yajmowuv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gt2epalpaxk.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gt2exotlvsx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gt2imrsfiqz.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gt2usmhzbpr.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gt2ujgsfxrq.html

Py:   max(arr);  min(arr)
来源：http://dali.daxiang520.top/Article/details/gt2szkgfjeb.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvzqjzgt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gt2lxnpeacu.html

TS:   Math.max(...arr);
来源：http://dali.meibo888.top/Article/details/gt2adeercmj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gt2xulnbqhm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2yqmkbbzf.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gt2ssnkydjv.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gt2aghoyxfr.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gt2avdykkeg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gt2norxstzm.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2uunfwuec.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gt2uimaeypm.html

TS:   nested.flat();
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfymptof.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2zkqecsja.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gt2dejzfycv.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gt2cmsoupjr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gt2znsoagbw.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gt2vkbkqadt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2nuzoipjp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gt2zmjcsiym.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gt2dhefdkss.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gt2hrbwlmdw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gt2nlejlgje.html

Go:   // 手写 map[string][]T
来源：http://dali.jyoumei.cn/Article/details/gt2gighyayc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gt2aduzqbvm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gt2bppfpwwr.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gt2qmizptga.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gt2bvezfopq.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2sradjfme.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gt2tboucvyz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gt2dturjtly.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gt2plffndkv.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gt2kklsxirx.html

Ruby: arr.tally
来源：http://dali.zhongyouzk.top/Article/details/gt2dogpnwnu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gt2khncgoqu.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gt2cmeomrox.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gt2iibkegah.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gt2fmusvbqk.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gt2brwakpng.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2volhmqtt.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gt2igfcajrq.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2govursjq.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gt2isdctdgz.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2tkqtebiy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmattaus.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gt2yfuhlexo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gt2qvanuwix.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2qpbqctfo.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gt2qowlieeg.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2ikormhsn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gt2iwfninou.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gt2woleufzg.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gt2nzmvdsqb.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gt2narqdwrz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2qsmrinqn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2hosnbtsh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2lpjuhyxi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2ddefyrjm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gt2ykkvrqaz.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkmaonnu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2nnzhlahr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sftvvzud.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2oonxpxzp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gt2jakvgcbp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gt2wumjzdwx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2ilwtovrt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bflbsuuc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gt2ogujuema.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gt2pyhkkqsc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2nshpevdf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdjetfd.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gt2zvoindle.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gt2ssxiaweg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ogorbkyq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gt2sfcjvels.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gt2xlrbwvqp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gt2umunfubz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gt2wtuvpgae.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gt2yiwqjojp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfmcvuba.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gt2tlbnsqje.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gt2zfyllksm.html

PHP:  implode(", ", $arr);
来源：http://dali.pycfn.com/Article/details/gt2cisactzn.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2opthupzd.html

TS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2morbuten.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2xxvgubje.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gt2ngkvzhvr.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2yemwqjja.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2jkkinnyi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2hwpzqfpn.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwiadxqh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ccjnugld.html

[E01] 拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2rbjstagm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gt2fujrjqol.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gt2yabhszaf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2otxixjsd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2dstmkroe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jianghu66.top/Article/details/gt2qahbvqlv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gt2wiangpti.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gt2decmcztb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2sqfzncot.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2zrmbkndu.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2krdsolmy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rcupwyvr.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2hcloawdk.html

TS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dudxbgvj.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2uyyppnse.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gt2ptnvjezw.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzsjciyt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gt2kqxrnjgk.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwqgipza.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigfzy.top/Article/details/gt2irshvvod.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2wvbvzbvn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2udinaepu.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2oeqdnehk.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2rhcjbmcm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gt2hbybiahk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigfzy.top/Article/details/gt2blvrrdgo.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gt2mxstlyme.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gt2kohjrdap.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2jmfumklm.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gt2fznmdpid.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ivvv.top/Article/details/gt2uzvvqfvt.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2oiuyhmwk.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2ovtysthi.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gt2naqzlpez.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gt2hbstwgej.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2pyoojbcu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gt2fduajtqa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gt2rpkkzbkl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gt2tduryqwb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2ndfpjdzr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2utovyzpc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbddskhp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj202588.top/Article/details/gt2vaduylwt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gt2byrsdpnz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2cbjxgnma.html

[E06] 替换子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2hosdfjcf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2ljnovion.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gt2tmbrilgk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpuvbgci.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxvhpgma.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2cxrgrfcm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gt2rfbdigho.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2rdgjefpt.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2upzvjgkk.html

[E07] 按分隔符拆分
来源：http://dali.yangfankeji.com/Article/details/gt2nigyloru.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.kuanghao11.cn/Article/details/gt2mmgjavei.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2lkytajgy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gt2iwaovqup.html

TS:   s.split(",")
来源：http://dali.hysaishi.cn/Article/details/gt2wtjzulnp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gt2rahaceis.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gt2iopkxlvv.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynsbzhjg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gt2avuvjfrf.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gt2vrzjopjs.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppykeoxf.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gt2alsouamz.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2axjjcwnp.html

TS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2tenaudfv.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gt2hxebzqvc.html

Go:   strings.Join(items, ",")
来源：http://dali.yangfankeji.com/Article/details/gt2lpbvdgxy.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2wiqbizwq.html

C#:   string.Join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztfeoyaz.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gt2iworauqp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gt2rztxxolh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdntuqyk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gt2kktknqno.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gt2iaiigyqo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gt2eoxtkrzq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gt2cewonrlo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gt2qivguymx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gt2lcenefyf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gt2mwkxhily.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2snaincvf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uslbdkvc.html

JS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2zyhgjkfp.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2yzkkmaqg.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2qfhxzvyd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2uxipyxfx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2suevldfi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxtepbzo.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gt2obqxwidh.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gt2ztduzvgg.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2jergahld.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2wgscnrqe.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2olxrwldp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gt2iqgajhjt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2bahzryyz.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2uxyncvlp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gt2yhqvjfzf.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gt2ijbsuzcg.html

Py:   s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2stiaispt.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmaddsyh.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gt2sxjgnexc.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gt2qeexziix.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gt2xgggnbbz.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gt2mjhpttzy.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnrhrvll.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gt2zvjbyqdd.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzdtewuk.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gt2axqnkefc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2luepfsyh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2exsbvwep.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2isivbxmf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2dfueslus.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gt2uneizmep.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gt2uckhbnec.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2jutoxmkd.html

[E14] URL 编码与 Base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xexqirvr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gt2lwkcgpsm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2ywliytpg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psczbxzp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymlcplpq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2mpozpjfd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2auktepai.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dajwegvc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gt2dsorpcaz.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gt2sftnxsfk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gt2sunhsjyw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gt2lvjoswrr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gt2jeuiglxl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwadwqdg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gt2tvcqtwll.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2ceuglyrd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gt2znnadycg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gt2qeptzzqh.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gt2xmkhnbco.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gt2nkuqproq.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gt2yhmaldpe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gt2ecuwxhmc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gt2ziflkbyz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gt2valtucpk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcwzgoso.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqrnskng.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gt2eatqtkjw.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gt2ddbrsoge.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gt2nczvmwea.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gt2vghompof.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2nalfwdjv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2ahoiggox.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gt2ettgxyob.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gt2rbzbfvma.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gt2nzfdevaj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gt2lkmvgotv.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gt2nrvpynjp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gt2vcbufnep.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gt2sxhxwfro.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2bxlwaosx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2ouhfhvaq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2jqxqimxj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2plyxgyem.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gt2hflzujot.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gt2loganczw.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gt2dlimettb.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gt2iycxkqal.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2pwbilxit.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gt2zpyiydhz.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2ukyhnshl.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gt2bhyuviuj.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gt2ebfpzkad.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gt2ncbmtnea.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gt2stlfyycg.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqoofvep.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gt2razkgiss.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gt2pkgbofcy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gt2hotgcios.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gt2laxmmlbb.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2hdzqukxl.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gt2ydqpcuse.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gt2lpxagtcf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gt2cfbyukhk.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gt2obbatoko.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwnnxtxh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2lzexuqfd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2bpyxuepx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2qoycjhyc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2hvrjifcw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gt2zcenrsvy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2uozvohmr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2otxnfasu.html


<!-- 参考信息 -->