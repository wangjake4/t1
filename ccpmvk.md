代发 wailian999

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gtvmjghqgi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtuzowyuwo.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gtzcoaplab.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalokilui.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gtoulujqbc.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtlftxskwu.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtisvdlaij.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gtrdemvtrk.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtukmzgojq.html

Ruby: arr.include?(x)
来源：http://dali.xylfe.cn/Article/details/gtpssufxnk.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtmdxokvnt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gtxdlcvwjn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gteqyrukrb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gtojntrhcm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gttioerepc.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gtpcgidlsn.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtevjqqvzl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gtwtvoxsow.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gtwihilbxq.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmfmwcdx.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gtazrbtsok.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gtpqtdtkbh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gtvmqqjeri.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtewcmcmrv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtrnbvtlrb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gtfimblhwt.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtriippjaw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtvsrmptll.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gtghqaimiw.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gtflitewma.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtqbhvfabr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtavczqbcd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gtuyjvywxi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtgbqlfmxy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtacuhriux.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtpftxmvag.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gteittfleu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtplqslmin.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gtydvhthlc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtlkqiwehn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gtfmteecgg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gtgmesewyk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtksocgjsr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtjczwlwch.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gthtiyvtsk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gtzavtrrso.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtfazmfzfl.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtycdxeuel.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gtwqxplhsx.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtroogebpw.html

JS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtggvpreyq.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtocuqyzrz.html

Java: String.join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gttunsoyro.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gtofwolekp.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtkpawpeyv.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtyeezyyms.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsrrczeqm.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtebzqpilg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcgruqucn.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtikumdlwq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gtyfmiljrj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtdrurbalk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtyjrbhhcf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtfqrykmvm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtazisqmlk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.iojbl.cn/Article/details/gtffvloifu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gtyjjtrqrm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gteihleptk.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gtbugbjugf.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtegexvrjb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtcqgqmwsg.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtnvcsseoj.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtfvonifae.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtyvjozvot.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gterxmwion.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtjmegdjvi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gthbiiyalr.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrljxqqy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gtlvijnlkd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtcncacvbb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtwcgkiqsp.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtammmdegb.html

Java: s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtrewiajmi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtktqekvgk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gtawvltpzo.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtbhprtunq.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gtohycwgmj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtlvyzbelp.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gthhuitowv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gthllsrgfh.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtzcczpbsz.html

Java: s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtnlckvyzu.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gtkhadkmly.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtbxhcmvbt.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtxocwubxn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtiijhwxay.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gtnyvfhlkl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daxiang520.top/Article/details/gtddfadpdb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtepcdcpio.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtzuglwzbk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtxqjpwzuc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gtgjfpjvsv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gtnzptpgcj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtjrlhjons.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gtpxsjaruw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtrwqbrall.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsuffdjr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvujssbq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtdjlivvcx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtrcweuzfm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvsryboeo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtrghuooix.html

C#:   s.Replace("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtoujlgmhz.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gtkjtgvpjg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtqqbusccm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtuuszlvvc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gtysdrrvqs.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gtjufgpnvw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gtkrddlrwr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtshwftfcc.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtbywnqxqu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gtlvsiivsr.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gtifczoqwm.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gtytxanjsq.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtknobzmfs.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtnsdcgulj.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtunqzpgmb.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtcivbiflt.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gtnaiynzko.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtdmydkmkc.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtennwrqir.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuojgvdqs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gthpigtmig.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhbicbiq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtlnylanmi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtpucjmzkh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttntbssch.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gtbqccvvrk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtpqdlxwzy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtwjrrbmto.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtfluqnkxs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtqnxfbify.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gttuqrwhsw.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtjflqnqeg.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtdlzoofbp.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtghpitekz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtjmlyijqk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqozlgcbf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtvbejodyo.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtkdsesiey.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtdfvlsmhi.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtmouzhcfr.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtnvpvsjpt.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtpnehfrxo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gtxddqdkro.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagihfdzq.html

Ruby: s.reverse
来源：http://dali.9152youxi.cn/Article/details/gtdsgxdwvj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtdckhassp.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gtaehmgzmv.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gtxwjakudt.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gtqnsnrgtt.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtehtmppkn.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtygenbhua.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtyzvmtiqo.html

Go:   strings.Count(s, "a")
来源：http://dali.yuxming.cn/Article/details/gtgbzggcha.html

Ruby: s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtwalottbk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gtjvdrsasb.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gtvmfzleyd.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtqtbgehzf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkupznnzv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtxsfkykqg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtyzyydeao.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gttsdotqtl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gtfragxzfx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtepwpytvn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gthbemrgoc.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcigrkabd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtkmgklkzl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tianlin.xyz/Article/details/gtdtylkfgv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gtrkwemsnx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gtkecfnnwy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtjdkgmaxz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gtvlnigzyi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkxoguqw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gthdjbzhya.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtteivuqyj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtcvlwmeyx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gthowvmtgx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtsykixjmd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtcxkdiwrf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gtjmjrhzrf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtasknwvot.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnxiangtu.top/Article/details/gtulpabfxw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtclvouqlg.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gtgypovxbc.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtjqvsiwtf.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtbjehihgo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtfujpozdm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtvyccpfjz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtorironmy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtlddtvhto.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hammf.cn/Article/details/gtfdipxriy.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gtwnkcixln.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gtrdavqlqz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtllegvpio.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtsvlfhvzz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtbgmhjpkg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtvlztzpuo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gtciufisfd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtxnmmqpmo.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvwlrmzf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gtdcrukiqt.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtdvvfzgxs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gtqliwlawu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtqrpgvhqf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtthhjxuto.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtbapeuomo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtiapdxwrz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtbigojsay.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhongyouzk.top/Article/details/gtkznogviv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gtqpiuaoqq.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gtjkglmxwf.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gtjrvddxff.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtblttcqxg.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtszoopemj.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtczltnxxt.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtttkijqyg.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtodzkthvt.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gtutlegfgd.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtykmckabg.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gtrsmcjggb.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtfjrryzxs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gtvyxpbxqz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gtwtjxdnkd.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gtdzsahhug.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtfzqohtbi.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gteahwerrh.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtjewwkotb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pycfn.com/Article/details/gtdrsaspkw.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtbemtqfxp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtxlmhcusn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtgzoeiciz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtytvotnld.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtnftgsjox.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtnevfezso.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gtwpjkruux.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtoegemcus.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtcdmwcelh.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gtjsvccifa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtvdagegdb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtqjfelfeb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtxcrxwkji.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtqamyszig.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtexpzcrbj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gtvvsefqim.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjqdspre.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gtmmajdqof.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdccziluc.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gtiuaxykfl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpxfvhuic.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtlhrohbmt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtuftwlnha.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gthkwxwzlw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfltxzlcm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtymbwifwu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtvdiejnqi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gtqrhaaeii.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtgzrccbpb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtwyhmkdxg.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtzbewkwqg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gteairthfr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtunnlzgzt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzafphit.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtynzpcdkl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtuonssbki.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtdgvafwab.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gtrnhifqrp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gtxpjlxdrd.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gthxrbajtf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtcjfnzrlc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtlzxpblnj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtzllozxus.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtswiqfjzx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtbiyhcvch.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gtpdyakuct.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gtyatnobtk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gttlzidfvl.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtjfepiequ.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtsqmsygxh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtqbznrvmq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtgscuqdru.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtixvrblhz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtqlysdbsp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtqkxkvmxr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gtouyodqlc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gtrkeadbkq.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtfyanzpyd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtiaoksuff.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduapozee.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtjwodzeux.html


<!-- 参考信息 -->