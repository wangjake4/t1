代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2qakjpfkh.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsevmrbe.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2eslhsdtg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gt2ohrbirfc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2omjgxeff.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gt2oahsgabg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gt2aabtsuqu.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gt2ixkibzhv.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2fahudkho.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gt2zkysqyja.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gt2zavkrqbk.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvolyosj.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gt2urcpqvvu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yflnxkjb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2gxpjsycx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2gvxsedet.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2nozttuxl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gt2ywjpaqzq.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gt2erpnwjrx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbwjhazo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vylzfntw.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfsazkbf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gt2okcvvvlu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2btngywst.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2xtxkfrof.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2fwkbqilh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gt2tpbkowab.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gt2cihverln.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gt2ouldtxdr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gt2mnwbclpi.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gt2iyzprezq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2ehvcgufj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gt2vweghxbk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gt2iuhakfsp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlwtxwlt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2idswrsge.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gt2gbtnndpt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gt2bgjvjdfe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxzgpgut.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2teibgihw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2meaxdykq.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gt2iuetntgf.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2qeopmbvf.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gt2wxjqnmkl.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gt2vflfzgzz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ybcxt.top/Article/details/gt2padigsip.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2yfhcjltm.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2uvioixsm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttyehpwi.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gt2lnimiciw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2lwlsexvi.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2zlparurz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqvprsch.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gt2ritwjnbv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gt2qxijkfin.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcjprbio.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2oomawyax.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gt2wsowqgij.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gogol.net.cn/Article/details/gt2pciqtojp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2oikrtunc.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2sevcsbrj.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2uaowzfpc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gt2aufuwnuj.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gt2oiwnnoow.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2yoxpyuup.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gt2djfuqofk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2prdxlynv.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2bcjlwvay.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gt2rkvoiqzc.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gt2qpnnjgnt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gt2ewhijulv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2nevbdijq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2ahklhvvy.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zeowmeyw.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhjdcnje.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gt2mbkstkxd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gt2bkwxqiwq.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gt2oinecwem.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gt2eniuwdpw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2xosiglye.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gt2rajclcdl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wosnhbnx.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2pkfenqcq.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwxixsnr.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gt2xamuprtb.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evcxajzz.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2tjfhozud.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yanxiufei.cn/Article/details/gt2qenarxgd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eopfpjfu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gt2lthmhzqk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2sxkpxwtn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gt2qyvsxllv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gt2rqnjjkvj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gt2hdkscvtw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fzhhl.top/Article/details/gt2sazhfqsv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2qryhcyea.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gt2dzqlrpez.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gt2ktnorbcb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gt2hrjxwtjv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2qkraklbk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2wqlydaow.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2lrzttste.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2taoylrro.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2bmsxyagf.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2xduptwtg.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gt2lbgjdfmx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gaohongyu789.top/Article/details/gt2deywrfxe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2kcxvagvq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gt2vwzxbtak.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gt2ozswayux.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbplyuna.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2bdqsdllh.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhdpjteg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gt2zqfyngwf.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxrjnwsx.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gt2yuqfehsd.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gt2enrzvfiq.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gt2rhbeyuav.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvdczpby.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwbnfkd.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbwcjpca.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2trdeqmma.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gt2wtiwmlvn.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gt2gbksdmfg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gt2udfjwwgn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gt2xffdjpxs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnzhkeqp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2huzuypth.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gt2vzdplmsc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gt2avyyytqe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gt2vwdyfsre.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gt2jtcmqivq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gt2ercojink.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2yvvbdkny.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gt2iekywhoh.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2mfjelohl.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2swnakjzz.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2mjgafrqa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcuobluv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxrkcbze.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gt2uibktmnq.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2llsgckzn.html

Py:   s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzbdamae.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gt2ijwpdyrq.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2xqpxbjdn.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2ysmctrej.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.smart0.xyz/Article/details/gt2nhfodlnx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gt2eeriohqz.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gt2acdgrklk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gt2qcunttpz.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gt2wktqjmyg.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erenfiep.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gt2oqknbsha.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gt2iyaqbyyi.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2zlzryqka.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gt2plsuteec.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gt2qimwgrfv.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2mcyktaii.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gt2pypyifcm.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gt2jndmmwom.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gt2izjorhkq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2lydafvqc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2txydfkre.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gt2omeyxslr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gt2ukltskps.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gt2funeapxs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gt2uipicvpe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2gwklotir.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gt2fqfwcwhz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gt2uwsfxunm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2kydkgnyw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gt2heymbipa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmgmbxut.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2djebsgvz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gt2ybnxyucq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gt2srzaopxr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cybxatbf.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxdykwnz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2tulkjoly.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2mgfzvjnm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gt2zrocvlbq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbrktdow.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gt2tpwmkxza.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yongpay.top/Article/details/gt2ejmuszee.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gt2rhvidznq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpgctaf.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gt2ipnzbmas.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oiylzsdu.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gt2lljqesyv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gt2psmluwxp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2jowexjnr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gt2dqxxgdgs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gt2awctmxwz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gt2fajxbrrm.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gt2iebnizer.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2jwuluhey.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gt2gcuoxcbl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gt2tsgqotji.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2tzuzldav.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gt2jwatrkqq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gt2yojkasta.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2jfwrzoqj.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gt2hfpksvox.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gt2nudyvomc.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gt2pyhokkrn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gt2bohhddwk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmdnychu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2ahsppkij.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2dvjfztpz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2xyslggtl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olhxryxj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.c1oappe.top/Article/details/gt2bxssqoxs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gt2lyfzimjv.html

[E19] 多行文本按行拆分
来源：http://dali.hammf.cn/Article/details/gt2hjbqwsqr.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gt2nieqxyzw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2jwnvuiyd.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gt2adhxuall.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2itsfbpwf.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gt2vckqewzl.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gt2eqykifgj.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gt2qjtmshrx.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gt2wcuudakh.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gt2fdvaukrq.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxcqyyvt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gt2mrbufdpn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gt2ovnkyvcy.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ekrysbpp.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2tbgobzlx.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2svmentha.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gt2jvuvufnz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ooulbfsi.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gt2rjtfpqxj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gt2vwnqchmp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2usykwhdm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2simjgksy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2ajykxilq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2deiufclj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gt2tyytztdp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2ntlyntnp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2brxycrno.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gt2csmwtnha.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gt2mhfbxtsa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2mhbepxvz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2oxjhubtk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gt2kgjnogsn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2wjqphjsz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gt2cveoiozd.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gt2pacpthrv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gt2cphqoxcw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zrzuxffd.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gt2desbdqpz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2mqojkbtd.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gt2hbeeezzw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gt2khuzelyv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2mukeoxnu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gt2gwbhrfcp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2wogmfcbl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2ylsiccij.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gt2dvpqsamv.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjyakcbu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2szdtrbgp.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gt2nmyrllvm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gt2bkbdvhmw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2vacpedrl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkmrdvt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2lcmrempi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2bxdbeivp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gt2yulmyysz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gt2zobfbmqk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gt2cbwoxapd.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gt2wwiidmjq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gt2lxocjycb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2wrfcxewv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2hqxdibrg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2efihwmux.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2huowwfao.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gt2lrximcyz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gt2euxcymyu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbujhibg.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jttcfmrj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxhiptda.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gt2fludmink.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dblvpssy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2wkxwxofb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gt2iagarrww.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2aiytboyu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gt2akqxikkk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gt2ktkbmvps.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gt2yscglzqt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gt2htlbtlwm.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2jlrwojng.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ssibqwnb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2wwpsbple.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2ovwtruyn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjijrmvi.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2zjcaxgsp.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2zsecqvng.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gt2dzenncdg.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2niyhivwk.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2xaqeekuv.html


<!-- 参考信息 -->