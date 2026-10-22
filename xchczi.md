代发 wailian999

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gt2yimhfkyc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2eujvqykg.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2ghvkswrq.html

JS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2ypgjlsfj.html

TS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2kdoaardc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hysaishi.cn/Article/details/gt2daihumja.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258888.top/Article/details/gt2qsjdowht.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2paneifio.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gt2curngdbc.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gt2ublrhcha.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2mwrwausw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gt2adrdmubk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gt2diedqola.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2vzufzzxe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gt2jjqmckew.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gt2ytyorlud.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yvedp.cn/Article/details/gt2etgjoqem.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gt2mqxjgjzo.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gt2antblzbp.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gt2eiujovlp.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gt2rffpysor.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gt2ksonfbmn.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gt2yqeehool.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmeusikc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2hgddwzhx.html

Ruby: arr.max;  arr.min
来源：http://dali.svipenyu.cn/Article/details/gt2semwziqm.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gt2axhxzxeb.html

[D18] 扁平化嵌套数组
来源：http://dali.yvedp.cn/Article/details/gt2zclcntio.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gt2nwbbhozz.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gt2gipgmnun.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlqmyeww.html

TS:   nested.flat();
来源：http://dali.zhoulong.xyz/Article/details/gt2roenfgsy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzdgitrm.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2zncuhpgu.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqvbuddq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utzazmpr.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrjkovmz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gt2wkwciiij.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tianlin.xyz/Article/details/gt2dhzzsflw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gt2lryaicog.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2vmgfqsoi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gt2jwbjirzk.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gt2loupkdtx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gt2tikzrpkk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gt2rrdovkhj.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gt2fdhfnmkz.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gt2eggdgdma.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2kbpghypd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gt2rbgmaqvx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gt2ufcvpghj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gt2zkqacgqm.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gt2qwudpdkg.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gt2ejzfakwh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gt2akeftzzq.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gt2maskhxpd.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2duysvktx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gt2quyifkpf.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2qkimewxy.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2nocpsxao.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2uhukeimf.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srfuhsou.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxcaejow.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2tcoagrap.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gt2dvzjogmz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gt2kutshpwl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gt2evunxvwo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gt2wvghtbka.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gt2pvwrdjse.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gt2slgfuuof.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gt2nllsranu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gt2wumwxavr.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gt2fbxbnsqv.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbkbxmgl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2nhlwhklc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2iozirhgn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2gvsdttvb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2ofubpfhk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gt2qnbqnhwq.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2qnxxwpmc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gt2ywcmqcjv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gt2nuolusxy.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gt2aronkept.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gt2gspkhmvz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lksxbkuz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gt2mgiakbov.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2kcxcaqcb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gt2raxayorg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ugmublwy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2oahfcwit.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gt2yhaampfk.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gt2qyhxzygu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gt2rirbxzat.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gt2bblakgrp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gt2inwqrafi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gt2szezzqwz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gt2dtmhcfqu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxkilvhu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gt2omzyalqq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gt2dptydjcz.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2ofvffzfv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gt2ssswddur.html

PHP:  implode(", ", $arr);
来源：http://dali.tanke756.top/Article/details/gt2imfdlyba.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2vtmcqjki.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfuyvzbm.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gt2tcylrklj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2fzspdine.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2nkqvfngm.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gt2xofejosx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ezbmscoe.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gt2uerfzbgv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vteproex.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2ejikeidk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gt2tdxwqivu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuxming.cn/Article/details/gt2ykynpjri.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2lhhnvcmd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2mfalcpxy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gt2mqjhuiqr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gt2lcbjuqye.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gt2bhutthda.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2yufvrcve.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gt2rqchikfo.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gt2tirqbbwb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gt2cdazpkqp.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2bdllksek.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glovdwbq.html

Java: "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2fisgchrn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okttztct.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2jazzibur.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gt2kjosjbns.html

[E03] 截取子串
来源：http://dali.tanke756.top/Article/details/gt2yqhmvipa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gt2pwtezgxk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2uwvzwnbg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gt2phsygbyu.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pznwsibh.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2eystqwbf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2yxbwgbwa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gt2fceagkdz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gt2viamqrix.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gt2uaqqbidx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2aahuzhjf.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gt2qgkwcbif.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gt2zskfdeoq.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gt2aezhefep.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2drwuifbx.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gt2llbtkelt.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gt2ygjeyvaa.html

C#:   s.IndexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2fqegkbhc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuanzhike.top/Article/details/gt2dkehasbr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gt2qxenjaiy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gt2wlhuaumr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gt2bhssswwt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gt2ukpwfcjm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2voentcaz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gotoacloud.top/Article/details/gt2hqvgcmhz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gt2phdlvonk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2oqghxpxy.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gt2wihpvzoa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gt2gacosdpt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gt2xxhacdwp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2utvtngyu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2vghhtknv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2bneccryr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhjxrxad.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2nbhzrubb.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2fbpfrqhd.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gt2dweglvpe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gt2rvpqkkpj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2mxexllog.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2roaoilok.html

TS:   s.split(",")
来源：http://dali.jqgfzy.top/Article/details/gt2dgxywbkc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gt2qekkahjv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gt2ifswrntu.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gt2lubvckfo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gt2ociucosu.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gt2udjxdofc.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gt2ulklycus.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gt2lhyysufp.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2kvgkfsru.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2vdxgsojq.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gt2ocpboaym.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gt2vyynrhvc.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2xoheabzz.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gt2kwcmiryw.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gt2ryolimhf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gt2yojviaos.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gt2ignfeyzv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idwkmemh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gt2kpkgbxrt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqmqcwlo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gt2oturuebf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gt2wqnldvih.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gt2ruefmgxh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gt2dsflqbbn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2yfhusnpx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gt2euajawoi.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2njwfjtkr.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2gpzmrwiw.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2xkykhnoy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2otmiyhkc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2dknpzwif.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gt2vfhoxvxx.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gt2lqnyjspe.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2lxwmnwvb.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2icziyiuo.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2lnpcjxke.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2fnjzsphy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gt2ueqnfvxg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2zfudpcwa.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2fhplmdtk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2tyfcayft.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2axlgdrqs.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2beqvzves.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gt2cgvxzrrs.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2gdzwtzgp.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gt2vvbxibil.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2liygwdyy.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gt2zkmxqebm.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gt2mygyrdnl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gt2ijbpbukx.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waiofien.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gt2zcqebgdn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vzkdezbo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2ucjawxzp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2kptqixwb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gt2ksmbmpoy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gt2cgufvtfh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gt2ulrjlspq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2abejhhjp.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gt2yetorsan.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gt2iocyndhr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gt2oypewsjr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gt2vrmqspof.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2bjzucmqo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gt2yuveowjo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gt2yorvvxjb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2dfatxooe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwykvcko.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gt2zsimylgd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2frmeeqwm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gt2hpsfjkjn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gt2itvuetlg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gt2nmripfyq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gt2kxelfssy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gt2evaciowe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gt2xklruwbm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dashuyun.cn/Article/details/gt2hqjmgzgg.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gt2ijyaajys.html

Py:   f"{1234567:,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swaowfsm.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gt2xiictueg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gt2foqceycw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2iuhlzdlb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gt2qvygubhp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gt2avzzqeyl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gt2kolohwsn.html

C#:   1234567.ToString("N0")
来源：http://dali.c1oappe.top/Article/details/gt2zlmydapi.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gt2mutlguew.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gt2ltwyqmql.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gt2wzxhhikj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gt2izxehtyt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gt2nuqxhqts.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gt2nfamkhwy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gt2ccxlwtaq.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlxqqnsf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gt2csagtxuj.html

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gt2xsguikar.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjsgaoiu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lcmiarsg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2copgiprk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmjlqjfs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2txcnzmkf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2qjnczkxo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gt2gtkqzwdv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gt2iyrelmxl.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvrgjtwb.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gt2xvunvfrt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2cmwrljox.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gt2mofcagqu.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gt2fcizycjz.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tagzpetz.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gt2xinbpvjd.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gt2crvzquxe.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gt2vnuagutr.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmtpmenm.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gt2gixptwjj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gt2mrzwzpsv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gt2qwcmwhtl.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vfaxkern.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2strorlga.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gt2tqkwtpuq.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gt2afnabxdx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhixingplan.top/Article/details/gt2rnfkhuri.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gt2rzchrxfv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbuvshky.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2bsugksmp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frkoxtzm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2slminbjk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2gytzxdtt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gt2kvrsstgr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2qzanudsh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2ozesxfam.html


<!-- 参考信息 -->