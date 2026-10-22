代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gt2eljhdqup.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gt2jtavqzxn.html

TS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2ctxjlepu.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2eeyyrqkv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2nqqqtbkl.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gt2wlqrtwuf.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2ftbcrybv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gt2uwfnbhuc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2prlgbuix.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gt2jsozuemt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gt2sbnqdwrn.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecqbscjw.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gt2ujpjlyrv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2csvthekd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gt2bveyfvnt.html

C#:   new List<int>(list);
来源：http://dali.c1oappe.top/Article/details/gt2gftdhnxp.html

[D23] reduce 累积计算
来源：http://dali.tian-w.cn/Article/details/gt2azflnokk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gt2qtlbnwgh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gt2fbrotwul.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2lskoctch.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2kiwxhuvi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gt2xypicnfn.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gt2psuwphmk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gt2fdmhoxbk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gt2lvywvqly.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gt2nonsvsse.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gt2cnkkprzv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gt2zxwushcy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2vfyvmygs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2ssvnrgar.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gt2uygywlrz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfemwzoq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gt2jpiipnvw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwefxaxj.html

[D25] Set 集合去重与交并差
来源：http://dali.chenlongwang.top/Article/details/gt2bqxhrbig.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2drgfqxov.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gt2ygqceuds.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.birdmap.top/Article/details/gt2jcsezwoz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvnighgx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jyoumei.cn/Article/details/gt2kfkyjfov.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gt2wnkwumxm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gt2wvbtrbrx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2gwevtjya.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gt2qivldrws.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gt2qgjhixrv.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2aejizlqa.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2spyhbxzt.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2horxuogs.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2gxjpckve.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gt2bjlbfjqk.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2dcdljkrm.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2jakzwfxr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2nretidat.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gt2nexsiaig.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2yzvkjuqr.html

[E01] 拼接字符串
来源：http://dali.jianghu66.top/Article/details/gt2lpywgesd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gt2mcijssem.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gt2vvanormd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2jgxgemfz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2ggxibnns.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gt2yoxoxnxt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ivvv.top/Article/details/gt2exyhyxav.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gt2qzydwueu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2ywhcloji.html

[E02] 重复字符串
来源：http://dali.cashguo.top/Article/details/gt2utbkodxh.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2fylsjalj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2xchhyhjl.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2hgldqqeo.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gt2nqbqfmyc.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2wxbimzwu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gt2xdkayhfs.html

Ruby: "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gt2cedlmlxc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gt2bgniqxci.html

[E03] 截取子串
来源：http://dali.fengsongda.top/Article/details/gt2jowqlmqt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gt2vtguiqee.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2niyxszem.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2oouwhqky.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txlllzir.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2suyloilc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gt2miajprxw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gt2zesplwju.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lcgovcqa.html

[E04] 查找子串位置
来源：http://dali.shuidangran.top/Article/details/gt2zuwvzgbc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2zblyixfk.html

PHP:  strpos($s, "x");
来源：http://dali.mhx1999.top/Article/details/gt2mxhmlrqf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gt2fvsfmwke.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gt2bxxvoazp.html

Java: s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2pponhvyt.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gt2pgfyafxw.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2qixewjhl.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2dpdjcpuf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzkawsmc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gt2rkgaupkl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gt2anvgwshf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2tmiyseah.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gt2enjdqslk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gt2elxxhlyc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfzpavaf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gt2febkvjmc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2ailryskq.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gt2hzvupwyd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gt2mumkbkww.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2iboosopj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqivmtyy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2jywpvfwh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2yoielicx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2gsddjnpp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2ftlwaris.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2ewbuznmr.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gt2uhiltgvr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gt2xkikxxni.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2jsbpapjw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gt2umqtvrgr.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gt2xgzxtddl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gt2tyzuybdx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gt2tpxzjswd.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gt2weiwumky.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gt2qsxxpasu.html

[E08] 数组按分隔符合并
来源：http://dali.sxryk.cn/Article/details/gt2fjkpgxow.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gt2derbvhib.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gt2fgkooaez.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2ebpujtdp.html

TS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2xtqedqly.html

Java: String.join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2fwvxxlcj.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gt2xaohgxjn.html

Ruby: items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2aqfarugz.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2zwtfbzwo.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gt2ooiyxvsx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gt2vlcycfcp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gt2hftvafxj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gt2ntgiiqad.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2fbsayebk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gt2jwtxdxlu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gt2lsgyuetr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gt2yocnzkcz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjrrvztj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvildnlw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2flwtcrkw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gt2saijpdlp.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2khqjmufg.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2nnngxxds.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2rzcsduou.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2safdezkx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2zrkewtry.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gt2bbjnzjdx.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2nseqyjev.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2etrkdqjg.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2eukunarq.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2gjvivxgj.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2fvkowiff.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbtkboeu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gt2yahyvyzp.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2jsrnesol.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2ztclesmi.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2cpoloyas.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2oghhqnns.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gt2fbfhmwzc.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gt2vekbsuig.html

TS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2uknypubr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgglelbs.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gt2jqvcjqyi.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gt2eemyrhbb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2ryyqmdtd.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gt2ghmihkxn.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gt2oylrhjyz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gt2lzhyfqpx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2qyvpwqca.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2zrqccnsw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2ddhquykf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gt2oqcpywgy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trrneooz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gojvmsov.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2gavsuqbh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gt2kqcqqtiw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gt2evmhzaoc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gt2pnbekysq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gt2flhlcdaq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2ppjdkege.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqpqxzus.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gt2mjdguokg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2phqcdxwi.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gt2swwagztd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gt2kdbmbtgr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2zpgfvspa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gt2hivvield.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gt2uuysmlns.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gt2pdqbvquj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nhlssqmk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gt2jlfcpnjx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yuccwxam.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2jeqxfvvh.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gt2kpozyjrt.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elijeezn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gt2yevfodrq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gt2ltsceiso.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfzxqlbr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gt2marucebf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aacbzuhe.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gt2jdjclrlu.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gt2yiuqxomq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gt2gsciwbaj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gt2mmzrwqzk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2bfjvnjsu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soysqrii.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sifutyie.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xziqi.cn/Article/details/gt2xshnywoi.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gt2acrbewgw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gt2uzafaruc.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gt2uaqvbpbx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gt2xjdxsmhj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gt2uxnzzzys.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2fkwlgklo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2xkbcrlya.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2qhhsogmf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2ifsflbdj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gt2mlwqvfrc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gt2iztshoxq.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gt2gyiecnic.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gt2xkcllhzd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gt2gbgxhmsc.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gt2ozvlakqi.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2hxmzkujb.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gt2itbyabyo.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gt2nxtaovpp.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gt2huwexfyj.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gt2phiardtx.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gt2gkizazso.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gt2lvarzncn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gt2otgbpbas.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbjssyhg.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gt2xioourcq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hteeydqs.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gt2eghxqhvj.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfylghzb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2ufamoudq.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gt2psflofle.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gt2orhjytdf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2bvpdwihe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2aeqhtfoe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvoowcds.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2zelbapmh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gt2burwijtn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gt2jgxqvxfh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2ekswwgrs.html

[E22] 字节长度与字符长度
来源：http://dali.xuanzx.com/Article/details/gt2iddjxrda.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gt2aaaowhqz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2kfhwahdn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdbvfdii.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2mypculct.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gt2dkxjkmho.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gt2thjexgjt.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2btpoaftw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwevrtuu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2idqdlnju.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gt2csnwcpqi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjwvhmdq.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gt2aimskaqe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gt2rpthanbs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkssohod.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gt2mlieocla.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2ntlwnozq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2delqppsv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gt2cddqwglo.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ceichrub.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2ujkrctrv.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2drazxbxe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigfzy.top/Article/details/gt2mjgoqfzj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gt2qkwqokti.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2rzdyoyus.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gt2datxvplt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gt2koyqrhak.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gt2fqbykvjm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gt2pukuxflw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gt2hwafudii.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gt2hmnnautm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gt2krbpgnnm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2djqzkvio.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2ofxrvnef.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2ggqjnbya.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2fuzdqkqh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gt2svnijkaf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gt2puagdmxz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ickllfov.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmyrztp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axryygft.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gt2ahdotvkw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2nmoqwraq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2ktkratbp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gt2ocrhlyuz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2vjkcgqgg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qckbuaqx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gt2bmejmpge.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2uurcpmfx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gt2iyoxipdu.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szypyubw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ijclgyfg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2youqalha.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2ikxuhdxc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gt2podrwjyp.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2pvgnentv.html


<!-- 参考信息 -->