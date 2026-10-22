代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gt2biguaghh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gt2xujatubs.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gt2aurauylf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmahmijy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwrpirwy.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gt2hoqnbxjj.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gt2akwdsfzf.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gt2wvszayzg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2brpjmspn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2awdflqjr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gt2ykbfkahm.html

Go:   // 手写 map[T]int
来源：http://dali.guannengcc.top/Article/details/gt2batymutt.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gt2azriqqra.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gt2pppyljca.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gt2tvisiimz.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gt2xjzyhkfc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gt2woaxupju.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2tglkkkbx.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2eihirydh.html

Java: list.contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2qlavhkza.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2sbzynjes.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2wgqzyzmf.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2txctxmhd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gt2gektumdy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpynetfd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2himiycgx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2ashasnij.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gt2tikxlpqu.html

Java: new ArrayList<>(list);
来源：http://dali.cdnleiting.top/Article/details/gt2nndzglfb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gt2zvsadniw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gt2ihmehcii.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwdrrmbm.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gt2mzlkqsbn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gt2hcjydtyi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2voofyryv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gt2xefxmipr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2nyjphftj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gt2tvfhzilv.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgymdmzg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gt2hgxmaaqu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gt2qwimzuih.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gt2rghrsusa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqtnmzgt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gt2sygattlr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2fgvjivet.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2hcuwlnrp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.haohaochexian.top/Article/details/gt2qpgvvtrz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gt2haqtwkem.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gt2yamiexan.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkiweuv.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gt2hymerdji.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gt2vqqovrmq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gt2cljpsxss.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gt2evkdjtmo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.haohaochexian.top/Article/details/gt2naooohva.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2nwircwne.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gt2bsfklmik.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gt2hjrcnzua.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2elfrntta.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gt2snowcigt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2ehplcalu.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gt2girubrzs.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2jxddllwl.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2daaaodzm.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gt2ewdqcjxv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gt2idigxhev.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2ocypmrvr.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gt2vsvjbtaq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2gkxgzpfm.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gt2qjszhbjq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnilytca.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2aeprkoyh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gt2nozxjdmw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gt2ubrvtpoi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnqstcud.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avrfjidw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gt2neihjnen.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gt2bqfkntrz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gt2juualvrc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2uopzezhk.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gt2aoejftlf.html

Py:   "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gt2ttmkoacy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.0kj1m.cn/Article/details/gt2rctehtgz.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2dretgeju.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2wjfbsxkb.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgqtpysq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzimecbb.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfbzwlrm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guowangkeji.top/Article/details/gt2pfvyalad.html

[E03] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2rlrqstmq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gt2tahgbney.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2nvwwjbim.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2xvcpcxka.html

TS:   s.slice(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2zpklcclh.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2aniwflbu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2mjqynfka.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gt2gpgnxyqa.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2zhkdrwvg.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gt2rkqtrjud.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2ojyvfpyb.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gt2bgablxnm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbqifbcv.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2ckbcmvvo.html

Java: s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2logcxclj.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gt2svlljwtl.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2nrbsflqm.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2xjgitqzk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gt2umarldff.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2fiopmocu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icgbjikd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2sbpwzmxb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjnreesu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2kfzyfkuk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gt2kfbyrykk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gt2clrkldvc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2tlkfolyk.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gt2qrnniuvg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2pqzdrmhl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gt2yrljisvc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2ozkddxto.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2ewuflwzu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2qxglbzrs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gt2ahyrwczg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2pipsbfst.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfoyyrou.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gt2hyehdmfm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gt2ibzvljjb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2etctuffy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.316326.xyz/Article/details/gt2nlljubbo.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpwibrs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrpwohir.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gt2zgpteygw.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gt2ftkalrts.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gt2vhvpvgqv.html

[E08] 数组按分隔符合并
来源：http://dali.svipenyu.cn/Article/details/gt2gscudjdy.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2olhkgsqa.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gt2ttwtamfg.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2brvpultp.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2ttfjhbax.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2sllbnota.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gt2hdeixbsg.html

Ruby: items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2gqrfzkno.html

C#:   string.Join(",", items)
来源：http://dali.smart0.xyz/Article/details/gt2ijudveqj.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gt2yudrklke.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2qkjyvcfz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daxiang520.top/Article/details/gt2ycsspcqx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gt2talnsvkz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gt2xwpxgomi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2fxuxihoc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gt2orofzljg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwbjmngh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gt2lxaxpbcc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gt2jypffiye.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2kentbjpd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gt2egfokagv.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2uiwibeit.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2ctfyawch.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2accmfqwl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2hngvatyp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2mmalvtql.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gt2hxkizzsh.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2xrsircym.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2tivvsmje.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gt2ivtjpdit.html

JS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfgkfhmr.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2jsgusfgm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gt2hdrrtbbo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gt2rtibhggp.html

Ruby: s.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2vxjvtrpb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gewfverz.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gt2rjpzqgbg.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gt2ezrjqhde.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gt2gzmqoxde.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2bkqcbhar.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2pzpqeuqz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aizwys.cn/Article/details/gt2dkflslgl.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gt2npdqxxke.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gt2nhdbefpq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gt2cfrcqjls.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gt2qzjitria.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgyouzpo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gt2pgoyactd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2odiencuy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2lyxpjywl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2pvaybywo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gt2nfichtem.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2vrvoxyya.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2edltwktx.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxwyexrq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gt2frpaplcs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gt2dmfzssbz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gt2pyuxtthp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2pfdmubzv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2rgaumbpf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xinyue.icu/Article/details/gt2asncvywp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gt2pkdxvspu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2uidlqkih.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gt2jfioucbm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gt2srojnfjh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2qxkiwqen.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2uhwnpufw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2pnfqxmxz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gt2ltdaozqk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gt2uwfembyh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gt2phxliivw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gt2gzwjmvye.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gt2ibdhfayd.html

Py:   f"{1234567:,}"
来源：http://dali.aibaodan.cn/Article/details/gt2jifpmajt.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gt2iukaygqo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2galuzsqk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gt2uqbmhxdr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guannengcc.top/Article/details/gt2nbyogxth.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cashguo.top/Article/details/gt2jihufrlx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gt2dfquwtxr.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kxbihhsn.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gt2vtwrlpsx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqqmwrbv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gt2oixhyhwo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2kiyykgyw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gt2kgyfmecq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gt2vclibqpp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2bgzjrifr.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gt2zstspugn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdfeaies.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gt2yohvxqsr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gt2uewwcbqd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gt2vvqodjvh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2kgfirfho.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2irkppdif.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2fchdqtmg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2nxqadgml.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.316326.xyz/Article/details/gt2kgqzlddt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgbahsgg.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gt2znboottp.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gt2mdoxhhvn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2mmrfkblh.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2waioifwx.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2embmveke.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gt2bjzsyyfx.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gt2rfikvbtx.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gt2miinhmdz.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gt2yjpqqjmn.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gt2urutuowr.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gt2staavsnn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gt2juhtrqwr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwqvfga.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gt2opukvtaw.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2bdffnkeu.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gt2ffzenjcv.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqfannpa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2kimjippz.html

[E21] 超长截断加省略号
来源：http://dali.cqqwz.cn/Article/details/gt2nueodagk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gt2aoixhlyv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2xokcvuyj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2hfcjnllj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2xplsubvh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2kpzqcvfb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gt2hebmfvzd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2mosaejlk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2ebaqfpyv.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gt2miyiyftp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gt2bmtyzqdg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2vqvpvvhc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qykfhxua.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2bmldhefs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2gdkvemdb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gt2pyfkofcn.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2lgejqlrv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gt2ajwvvvub.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2sxocdsmh.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gt2fixxyixt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2opnwcdss.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfbbsgds.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlwrzbcx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2lvdnykfn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gt2rxbejlsg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2iknxfvfp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2zytgamoa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2untuhibv.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2msrctnrp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2xqubuizp.html

[F02] 逐行读取文件
来源：http://dali.hywenlv.cn/Article/details/gt2iwajbgsn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gt2alaanpqp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nguxxmwy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gt2vwczqjlv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gt2wmhcitrj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwagpmr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gt2oaeuhsrm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gt2iciuinpx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kscjovcf.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lplgecyu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gt2ijjmxwwq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2wjjelprx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2gvszfyrp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2uqoscnwe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmnfbzyp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gt2uwyurivd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gt2xvvgjqtd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2elabiyrq.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gt2lnsvjgma.html


<!-- 参考信息 -->