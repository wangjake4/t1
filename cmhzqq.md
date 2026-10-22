代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gt2vcejrnyu.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gt2hcwbyaxi.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gt2gtxnkabm.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvfjoics.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gt2muikjhko.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gt2aelilont.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfeeadpu.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gt2mqxuncof.html

Ruby: arr.tally
来源：http://dali.mhx1999.top/Article/details/gt2cxjkauvm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gt2gryoerlv.html

[D21] 判断是否包含某元素
来源：http://dali.cqqwz.cn/Article/details/gt2zfvezzib.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gt2vsbjgqnx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkqbgegt.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2xgfmdiak.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrtlkuhy.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gt2phjfflfw.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2sktocqrw.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gt2bqzlqawr.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2vispiusy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gt2utskqlxl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gt2lgcduzll.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cashguo.top/Article/details/gt2xofvocfu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gt2quygzoxb.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gt2mgjevhxo.html

Java: new ArrayList<>(list);
来源：http://dali.xinyue.icu/Article/details/gt2grfjsktz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gt2dagzzwqd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gt2qtjvvwga.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2qsxotjei.html

[D23] reduce 累积计算
来源：http://dali.jinqigufen.top/Article/details/gt2rwuzftlv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2hhtdsrjx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gt2uygrgjun.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2dangiqds.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2xknlxqzi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gt2aovaevwu.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gt2cwvnsudd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gt2fhiaynhv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gt2seiyciic.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gt2daemuhua.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gt2kbngqhjt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj202588.top/Article/details/gt2hiwjjffo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjtqilal.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2eszcirci.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gt2nomwxawe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gt2mtdyjimo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gt2nvuyodeo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zycfv.cn/Article/details/gt2pztlrlip.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gt2sqfticra.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gt2mipxxfng.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gt2brahzfss.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gt2awsyjggw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gt2tohamitu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2qickjqxm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gt2gcsgufyr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gt2vdabwvtk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gt2iuzihuov.html

[D26] 数组转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2zncptyhh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2epxoajue.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2fibkbbut.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2ohaslilx.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gt2zgknfnqi.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gt2yqlfoqcn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gt2lvnvtnlb.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2ymtohzaj.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2inphxsel.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dntzrati.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xobvevex.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2cbebgziv.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2duztstjm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcnwpsbd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gt2frgnycum.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gt2fqyjmjee.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2gsjprkfw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cashguo.top/Article/details/gt2hrbaljsq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gt2dkgtnebw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gt2tnbxyjxa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2odzqgfkr.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gt2kcfdsyjj.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gt2wetnipcp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seygwxmg.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2lsarzjdx.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2evmfjymv.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2yuajjwnq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gt2qtpptbyw.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gt2optiqbyc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gt2erzkqyqk.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gt2lfovlyzp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjtyxmqp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2rkploxyz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2padzjjbc.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2ntzhpnfw.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2vqhvxcff.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gt2jhkprmzn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gt2fwbcsnvq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffzpniyz.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gt2rrhjjzzt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gt2rztkzkdo.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gt2uyxxnzpb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gt2karqjvxs.html

TS:   s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2gosbtzvl.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2cugvckuz.html

Go:   strings.Index(s, "x")
来源：http://dali.yonumen.top/Article/details/gt2kjpgnspm.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2yiqlyxpd.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2cnrpnxxv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gt2lrpapmqx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zycfv.cn/Article/details/gt2qjtbdbul.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfuyzvnm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2tyxmbxwo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gt2ekzgswuv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2gwjyziwm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gt2lkyajixv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axpjwaci.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2qfsvpzvw.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gt2zgylqyjn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gt2mwuzjvpv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gt2pmrlmjnu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sntlfyzd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2errnuqqj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2qolxtnjv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gt2iwwbpcyv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2vspsqxkr.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2ljxxyyiz.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gt2uvhoscqg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gt2hkrmbzng.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2twpkiwuw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2yyvjslmq.html

TS:   s.split(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2xpoeywbx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gt2qfibcdwg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gt2kfohmfev.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gt2jevryryi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gt2umqeelnf.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2stzrfvsj.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gt2iktxzvpv.html

PHP:  implode(",", $items);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdhpclct.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2vpmwbcls.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2rtuumllh.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gt2fozuhjzl.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gt2uzvmafhx.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2jqoizucd.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gt2jszguaga.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gt2fxiqhjeo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gt2vhkxnzbn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2dvqwiucb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2tlxldujc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2rmbjbwoa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2sxmkxwyk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gt2ldkwwkos.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2qjjzbedk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2qofezfpd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cucudq.cn/Article/details/gt2zcdeakzp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2sykzxwjx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gt2wuipqkoq.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2dkixdkny.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2qzaxhpth.html

Java: String.format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2bxhucwre.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2mfxooacp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2qizafrnx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gt2fqoaufsq.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2oeqmmgpz.html

Py:   s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gt2sknjhwqb.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2drzvkkqh.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2utnwvrrt.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2qiyiwabo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gt2mtlmauin.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gt2wadzoqqw.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbskjeee.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2vkmjbmtk.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2jmykytlf.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbhmitwx.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2aycjwbjr.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2dqsydape.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2cddexfdo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hammf.cn/Article/details/gt2uarswhfv.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gt2iiaukvxm.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gt2vziulyva.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkbhrbfx.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2lswoguml.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gt2nomsrbjn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gt2vhbzqfbw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2ytefjlsk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2rxkqxfty.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2wrznzyib.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjgimmgh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gt2rcuecyzw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2nubjjeql.html

[E14] URL 编码与 Base64
来源：http://dali.shangyingyoupin.top/Article/details/gt2mchlmscu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gt2jxuwnjxf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gt2wyokniwi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gt2rzmbjnxv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ojdibkyc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2lwuersov.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gt2xifyvtai.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gt2fykzdusy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2umuoazza.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gt2wwamzjpi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ykgnkgrj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yspcjlmv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2izoadnlu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gt2otthkimg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gt2shikigze.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2elkqpgtk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gt2cutsvqjm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gt2gymplvwb.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gt2hmympwty.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2xygaunwv.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gt2lgjmguve.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2dcdpqmbx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gt2tueymkva.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gt2rqnsepsm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvisldoe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gt2jxmclanm.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gt2pgcqqtru.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gt2cbeittix.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gt2iyibihyz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gt2gmgptsiw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gt2jnvbhcsp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2hpkickph.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gt2ydevqpky.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2zdkbkrtl.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gt2vfbkpnlo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gt2eqcnawqh.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gt2gjlyljja.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gt2tjbucwyt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gt2xvbomhbi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2pcjgknyy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2iotkfakg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2vlluygod.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2nzmprito.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gt2tojbqrnu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gt2cdtljirj.html

[E19] 多行文本按行拆分
来源：http://dali.cdnleiting.top/Article/details/gt2vbkbckim.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gt2xprbqghv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2irvklrva.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gt2ojzcdbft.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gt2asfkatkv.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gt2ukygqllr.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gt2khvqozhx.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwsbhsqa.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gt2ebicmfyf.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gt2ehseoock.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gt2qrmufpqp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gt2nxpanvjb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gt2ksyspgot.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gt2evbzqqsg.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2wysaswfb.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gt2lpmiibkm.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gt2yxrgtegj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gt2wcdisqvs.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gt2jvoilbkz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gt2pkqhttof.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2ltdwukxc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2hkxsyyaz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2rcuiljab.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2pbwbtngr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gt2evdzguuf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2inawasoo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2wqpytnyq.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gt2cfeszgjq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gt2irnxeerv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2kntdastq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2soszqwyl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2htfnnanm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gt2ivdybknp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gt2urogpohf.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vutdovib.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gt2xjewayuh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2nrbnkutw.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gt2xpjcwblk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2wewudkgn.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcowmvli.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gt2budwbajy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2svykxbez.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkmolkgr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2hogcuejv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2jpjsbjuo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gt2tikkmspz.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2lpeklvdd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2iddupuyg.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gt2ornuqlkk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gt2chffpwsw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gt2lgknpsos.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gt2gzmnuwli.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gt2xlxtncmq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2tsdemwnt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gt2evoczhkj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gt2zwzaqyxc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gt2wfpmlvlj.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gt2mekpylba.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlfkuqdv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2opkgcpcy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2hvzbsmnm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2ybnmlpxb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgdiktud.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gt2sloxtqdr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gt2iyeobljx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2yeukizzy.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gt2zewvjxis.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gt2vwkfmaua.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gt2oxmmjdzi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2rhgnnsge.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2vexyknsu.html


<!-- 参考信息 -->