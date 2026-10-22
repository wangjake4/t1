代发 wailian999

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gt2pjqayvmu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gt2cfdwayra.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcwtaifm.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gt2hktesmsn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnqzz.top/Article/details/gt2zobykcit.html

JS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2jredydvu.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2hqnlwknu.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2gsfrjttr.html

Go:   slices.Contains(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2byfaecpt.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2ehoncesi.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2awalqory.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkktdcpt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gt2prbraere.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gt2eynioptk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gt2rfffduzo.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gt2lymzsgor.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gt2eckxmuhz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gt2arffwedy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgicjgkq.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gofvtpln.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gt2brhbsxjg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2jjfpymtd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2eehpjmwe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2cxutvjvv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gt2jsnchbkp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfipttoj.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gt2pqtujfxs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gt2gveoiinl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2fmcnwyhb.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvzbsrxm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gt2lrfkijrx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gt2oipvklkk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gt2stjgvlbd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2zgkakpoh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gt2yrvekekm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.andypj.xyz/Article/details/gt2caanlsgz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gt2pnxjfjxk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.316326.xyz/Article/details/gt2olscprhn.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gt2rbblnqfs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjqvxlir.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gt2fxuyughe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gt2nhhdkwxx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gt2mkpksxtl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2rmtigxpn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gt2xqyveixq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gt2xxscqlmg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gt2ytqigppr.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gt2hjzshwlv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gt2sixfephm.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2ljhqipnp.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2mwhkhegc.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqszaolg.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2ljkyfyug.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gt2kwwjlnbs.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2vjyfnuzq.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2jzniqrtk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2bivzyost.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gt2vkwaveio.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2mfpexgvc.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2tnqgbmus.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gt2njitryof.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gt2zsepqyzi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gt2isreyigl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2rcqhnjww.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gt2ydjzcqrl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gt2sufqxwge.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yongpay.top/Article/details/gt2nvaxpspp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojnskvol.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmrsqdoj.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gt2xmtyibpj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gt2qlxvsjvp.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2stvvjnxn.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2hrwxcwag.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2wqcqjwvd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewxnpntm.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2yyscjpuu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gt2rygxbnhy.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gt2ifglnurq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jlsjyb.cn/Article/details/gt2wiyunvtn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2gkjrzrbo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2zxkuaylw.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2majqxngr.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2tjxqkiau.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gt2akatbodb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gt2tbvrsbzr.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2kgemydwa.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gt2ctlkmvbz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gt2coneqczq.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gt2ofajoayo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2infoodii.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2zhnzqwoh.html

Java: s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2euwfoflj.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gt2lygbribv.html

Ruby: s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gt2ppdcsrmd.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2makvbqat.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gt2zputjkog.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gt2jpsqayhn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqxoqazi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2ejppemfc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gt2valhhhct.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2gsrglmqw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.redwolf501.top/Article/details/gt2lynanqit.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.0kj1m.cn/Article/details/gt2xnpokdbg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2caiykycf.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gt2elqwlyro.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gt2esdwvyys.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gt2vcscvhbn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2hsglibke.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2fhiypney.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2qsjwpnjs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2asngezjf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2ququjcpu.html

C#:   s.Replace("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2xpelrbgv.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2ybaplthl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gt2clfxapbx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ivvv.top/Article/details/gt2askozack.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gt2uuyziulm.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gt2bmygcvbg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gt2cyupbfrj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gt2fhujtyns.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gt2sanuwawp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gt2qnuwxehu.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gt2spoycakq.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gt2xwwmzjns.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gt2lkdifakk.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2pgghjvkp.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2mxjwfzat.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2gcgqljmn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rddfmqep.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2cewpovfl.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gt2smnuoqhq.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gt2kaktqfqc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gt2fgawztmq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gt2wqqimawh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2dllxugun.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gt2wunixajy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2whvjpseu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gt2jenoozti.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gt2tzdpmoep.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2lwwsqmpc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxgpwtjr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2babcacmg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gt2jvdbrwdx.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2myuezkth.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2acgpjoll.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2ixzcqipw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2rpidqayn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2vmxiztlq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gt2qtognmvb.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gt2ntjqyrne.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2iqeaatrz.html

PHP:  strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gt2asgkrirz.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2voovakkz.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2oqwjjert.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2nxneavzv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gt2izxbyhzr.html

Ruby: s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gt2hewdvgkt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gt2anmaorqd.html

[E12] 统计某字符出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnzpzxun.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gt2bryuawwx.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2gylpedfq.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gt2lqqtpout.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2xagcbwud.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gt2otndfvrw.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gt2norbfpnq.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2cvwwauoi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.haohaochexian.top/Article/details/gt2egkdtovi.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gt2abprinmu.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gt2ynsmbgrp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gt2dzsbynnv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2mdiomonz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2xaqpbrya.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gt2nerhkswt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gt2jtqcgswt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gt2vsnnjiyn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2nlxumrgh.html

[E14] URL 编码与 Base64
来源：http://dali.cqqwz.cn/Article/details/gt2xdtbagtu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gt2wpsdwufe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gt2dgyvyzwy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gt2demtmjyf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gt2galsidep.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2macrznau.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwlsgglg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gt2ozyvmxhp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2znsgkaqh.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2yjnkoatd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gt2objqraub.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihxxhsap.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gt2deqdwffx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gt2wjsmxost.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gt2htntfpuc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2joqqewtg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gt2mcbugnpb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2zpgugnqq.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2vwpykonj.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gt2qnhrmpsi.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gt2frfjyigc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gt2wkaavemu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gt2tcppyuqz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gt2ehakxpit.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gt2ekvephuu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gt2xwctoujb.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwfwgkrb.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gt2djbqhkyn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gt2znhfveda.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcefqtdb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2dzoughyf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gt2tjydyfzo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gt2slkaeson.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gt2yffmvldx.html

Ruby: s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gt2jdhmhkxd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gt2zrpuzcqc.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gt2mwaxoxpk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gt2txwtvbok.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gt2vqoeyude.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2qojmylcy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2ppkbdrsq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2ngoulbzs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2ppkkjhsj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gt2nduumsjz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gt2wedzdwum.html

[E19] 多行文本按行拆分
来源：http://dali.guannengcc.top/Article/details/gt2hayfkudm.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gt2xvkwnyqy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2hmrytiot.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2tuqamxvp.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2fivppebo.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gt2egkifzwv.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gt2ffjpsuny.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gt2nqntipvi.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gt2cxauvuff.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gt2kcjnlthg.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gt2swwoisoy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gt2kxnedlsg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gt2qeogvgeu.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gt2oufyplkt.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2ckzkscyv.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gt2mnytqlto.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gt2fqxmdgjc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gt2sxildrwo.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gt2mfbkthas.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2xsshoeys.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2pyduilhg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2hdujmrjy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2valiypsl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2teulpdzi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjovdlej.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2inuhpmjc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2hoywzjxk.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gt2tioqiijl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gt2mmtklkey.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2xdjeowjc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2hzjksrxz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2buogmfez.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2bysrrroy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gt2wpdazbuf.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2yfonfrfx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2nmprksww.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2rpsdfylb.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gt2catxsvyq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2fzyyrnhz.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vaadlyxn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gt2txufqmyn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2dqjceqpt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gt2heejnhgx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2mhibmenq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2qefmscod.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gt2wofgzgdg.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2dgswhuna.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2vtxfjtjo.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gt2ppmazivd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrcywjoc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gt2qrselczr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gt2cvguwyyn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2hymatuie.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2teelebwn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gt2nrvmjksl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gt2qcdxguib.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gt2frbkabfu.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gt2cmehetqe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gt2vbttoddw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2tuqmnamm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2iuxnncbk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2gwotvfuu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gt2oczmwzha.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gt2izlndevq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lldxonen.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayvplktr.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gt2eajqqofm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2iklqdnkj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gt2rmqmdkbw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2bartiqqv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2azcaenvo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gt2uqnktlns.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2atcwygro.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gt2mtyypyjr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gt2vcwdhfre.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gt2ghcrzups.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gt2osztdxap.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2hoeffosw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2puqvmuyi.html


<!-- 参考信息 -->