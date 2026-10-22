代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtvdglcpue.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskgxecul.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfnjsson.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtsoqytlhb.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gtojcwqdxr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtfzwrydrw.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gthkkhenru.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtyfxzjroo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtialesbjq.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtsekuxfjn.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtxjuobdpk.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gtsoarvdko.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtugojrvvv.html

Ruby: arr.include?(x)
来源：http://dali.xuanzx.com/Article/details/gtwwnrxadl.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtjmfbyqlo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtpasevsyu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gtmlludjxi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gtwbvzhdqu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gtjwbebtcs.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gtiyczynmn.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gtktjgmbvg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkbozozu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gtpeaywvux.html

C#:   new List<int>(list);
来源：http://dali.jlsjyb.cn/Article/details/gtodcifhia.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtkgkfpmzj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgxxeyfh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtxqozfboe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtdpagrhmw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtuajjrjdp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gtrojyctiq.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtrwwqtemr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gtmsvdsnda.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gtvffvoqrl.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gttnwwbkab.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtbqoezxst.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtjjqrgufi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtjxvazwur.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtehcfllcs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtobbgtliw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlrhxtzt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gtmbvfsipe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gtghjybvqs.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gtuhmmxoen.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yangfankeji.com/Article/details/gtlizackos.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gtjkqafiyl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gthhxbdbty.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gtmymbgqbn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gttlwfykzm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtanekjgth.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtegtcnlax.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtssefvitu.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gttbvtbelr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gtypnavukg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtnbnqchiy.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtsxfstowg.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtpylwyvtd.html

Java: String.join(", ", list)
来源：http://dali.yonumen.top/Article/details/gthtglrjso.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gtruoithwh.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtqlitxsow.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtbzedvcol.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjqgirens.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gtyhnuaswe.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtlxevzxeo.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtouenkaid.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtermurqxc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkriuyyd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtawuiuejy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtkjeiebya.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gtezhqnyxu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtssycemmk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jiagoushi.top/Article/details/gtdsxcgjwb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtjyacgvxu.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gtdpcninqp.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtohixurar.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gtqpwcubsl.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtumxnxmsf.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gteqdvpehd.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtpfnkmqch.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.snrcjt.cn/Article/details/gthtnwwktc.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gttprgvxql.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gtdtdvvyar.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtgqqclnmw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenjidiqi.icu/Article/details/gtimkdhavf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gteloqezew.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtkmqyjkvf.html

TS:   s.slice(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtwzfcxlhn.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfmsudni.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gtigzejwno.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gtcnmqdjoj.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gteuqnmdep.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtttvlhmez.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtenuwptpf.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtkmwelkur.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.9152youxi.cn/Article/details/gtdshwdqwm.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtwkvbzufo.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtgtkfojjs.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gtdtcrqrty.html

Ruby: s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtgwdsrnob.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtobhpbjqr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gtkvsxudcf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gtqbqyziiw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenjidiqi.icu/Article/details/gtalkovldb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtgfruxfca.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gtbxwnzkqk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtgvgatqra.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhiwuduotai.top/Article/details/gtexmnesyg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gtxgdlxlko.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtqrqwbvml.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gtlhkbjsub.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtsuqpkyiz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtuhpoqjym.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtavlmlotj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtotulaigi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtpkrmsatn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtnhwhamhn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtageewxnt.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gtskeqgktp.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtdgflpdgk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gtqmwneulg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtbbsuijde.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yongpay.top/Article/details/gtzcwlnpgq.html

TS:   s.split(",")
来源：http://dali.pycfn.com/Article/details/gtxejhulfu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtgpvbysed.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gtqeagmrsp.html

Ruby: s.split(",");  s.split
来源：http://dali.daria6918.cn/Article/details/gtaqajwmrz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtghzwmufn.html

[E08] 数组按分隔符合并
来源：http://dali.yuanzhike.top/Article/details/gtrzpqovbx.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gtynfblhxg.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtstrtjhvl.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtnhcgmmci.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtmzsavjwh.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gtsfeqqipk.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtvzsannqu.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtfmaztczh.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtmjycooui.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gthqstcfnn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtuifuxogt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoatbwef.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtpjlekqxr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtvsdsyclg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtusosxtkl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtdenfihpm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtgjhlisqc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtppaowoiy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbptuhqgh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtmasopots.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gtvshvcbbk.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtdrjnvbdq.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtqjwrwijs.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtilznltaz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtynmqkenj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtmojgaymg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gtntzzmvbt.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtnnifkdph.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtbrejeoin.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtoaxdrqux.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtxectmpbu.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtqmddsvpe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtltzitaer.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtpulxkklm.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gtrkozvyge.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gttlvzkdkq.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtpwnxkrxg.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtwivrnkjo.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtpxifiwpo.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtvjrehhoq.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtbjajfikd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqlhfgkv.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtfleaoern.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtcnxjkgei.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtghxzmsdr.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gtbwjzxmpx.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gtgumizndo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmstftxdz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthnhickvv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gttwmgpnbk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtojuxxhtm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtrappqnpb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gtzqlpdsjl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtxiporxix.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtugkicuoz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtwoesgiuh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gtkezmpigk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gtuplqslpw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gtraqtywyn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtsduueozr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gtretztpny.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gttesbhfiz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtvwpfzbbc.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtfcvdbcwi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtukqaduzw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtgoygxvvw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtfmmznmti.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gtjyzmvabi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gtddifnlay.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gthuhmidat.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gttdmqufzg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtzulwepms.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtwxxzklfr.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gtpwtreenc.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtorwtnptx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtcpbqqagk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtjxjyebea.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgnclmpt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtmljkqojm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtpxrtkqra.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtwdoaudzn.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtsumobzms.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gtoajfouqx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtembsubtb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtplcfpaht.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtxjzqlspx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gtdcngfuwy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtqynbrabl.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtyfjtvmic.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtwsgtdlqj.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtuywtgsel.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gtdxqfegvu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gtvatnjkoz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gttdmaeilw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtelmllbkn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtaonlnxlf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtnbhyqqny.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gthaeuytgo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gtmcfvugzz.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtqcdknuqq.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gtckmhhrps.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtbcygrolr.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtkcbbgvvb.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtobdzozxv.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gtaxvpzauv.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcujbfydq.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtbopwoxhh.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gtpuhgqpvx.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gttggpxplj.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtjtdntdmg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtotcxdeun.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gtrgxkasot.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gtlknadtkx.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtidbdllck.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gtpkwyfebs.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtiidlcdyb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtjtiwnvmi.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtlfkgyjlv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gttzrnchlt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtaedsjumh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtsrgyslzc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gthtscfvsg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtuptnfgad.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gtgbdwzwtz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtxiirvorc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtoirzvezt.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gtdzxnjkzu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtqnfmftga.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtlqqrtupt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtxpxydoil.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtwycwlxqq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtptjgnqli.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gteimttuet.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtrdyyykra.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtgfcpyvzv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfqnrlxbf.html

F. 文件与目录
来源：http://dali.yj202588.top/Article/details/gthdednzuk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbdgcsfuc.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gthzeeemaz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gtcmirhjwz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtlmiynkec.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtgbtaojzp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pycfn.com/Article/details/gtujlchgzn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtvsnsfvxa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtnulfhzyt.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtmvqnjjsf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoaqitrt.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtsfnhdjuq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gtujqbuccc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtkfbaqsbh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtmimppcha.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqjfbluxi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcclgjoi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yongpay.top/Article/details/gtbhsswbtf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gtjzfwjoiy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gtwoiztsag.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtgayeyqaw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gtrkrvikaz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtxvhbkaxg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtqlbgwmsp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujdvruhm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gteooknpio.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtjblnmckz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gtoniyiuqw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtefuxjrat.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gthxkkpgxy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtwnrvnssr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gtvvjgybuw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtdcmxirev.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtiynootuu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gtrxbazibq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtjbgwwusi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexozxfwz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxlscjxx.html


<!-- 参考信息 -->