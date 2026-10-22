代发 wailian999

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gtkgkiewpk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gttzbgyiyy.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gteejtrheq.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtxfkqliji.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gtznrfhgpu.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtpajfrumf.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtmlslpgwl.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesohfqax.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtwwyjnbrd.html

Ruby: arr.include?(x)
来源：http://dali.yj20258.top/Article/details/gtzzazikzk.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtkwyxakok.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gtxwfldvxl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtobkfeuoh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gtnmipvpes.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gtomlbgham.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gtoooiodnx.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gtiilwzxcg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gtcusdqcvq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gtooavkrhx.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtcmwzjilr.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubsidfrz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtzmuqffyz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gtsenhhkxt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtcwvrqpmz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtzrruaovm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gthszftgzw.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtqoaadfes.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtudarrjjj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtskszxb.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gtkqyxwfaz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtmceiljfl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gtydnwnhkp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtzvjajanm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtudcxxzbt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gtoeekneoi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gtqpxmgmfm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtdrlswmou.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtrcdxummu.html

[D25] Set 集合去重与交并差
来源：http://dali.aibaodan.cn/Article/details/gtxnxrbnls.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gtewuwqmmt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gtuwlhmivs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtrjqevqqt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gtnxzzwnmc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gthottlpfz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtpjzyeine.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtowwoukja.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtlkeexmwu.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gtimibmlvr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gtvbcxqhfs.html

PHP:  implode(", ", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtwpqhsqyv.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtppcjbfbr.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtwhdeluqx.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtwujbfshd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtqpasfvkf.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtyuztcwci.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtrjfbtrnk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtccxbrxzh.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gtzuoidawd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzgquiogj.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzglpstf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gthkfymhwt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtqmitcrpy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczqmmzfl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtqijtdhti.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gtihwwiwom.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.0kj1m.cn/Article/details/gtqasyolps.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtnrzsltyv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtystgqqux.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gtfkrxsyew.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtnhggstnq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gtnzehxhwn.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtyprgtteu.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtafhzplvz.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtldjhujvv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtvoitszyp.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtdlkwgiyw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtlrwjqhtv.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtguccdbqc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtyprulelm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtgllraeec.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtuszseebh.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtstybunag.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtfqlkcabt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtbqahynpf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gtehuybudg.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gtjnxqydlw.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtyqwiduzk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtlzoxxmuz.html

PHP:  strpos($s, "x");
来源：http://dali.hfpthk.cn/Article/details/gtqsqdkugc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtnshsfbto.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclssajym.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtjtfcfwir.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbosixnht.html

Ruby: s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtdyzdsqge.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomfabsrq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gtdjpyqpht.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yangfankeji.com/Article/details/gtbjlxwtai.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gtuzkbpnyr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtsynliqhj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatfyqgwi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtzzopxerc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtibsliuww.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtcwahdwou.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtxjphmmgd.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gtgcpvpvfw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtehwnwiii.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtrjdcqxeb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtyxwyeuij.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtlxzfvyqx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtrdilctqj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtdrsgfhbv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtfumchovt.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtzeprlanh.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gtftfxdlxh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gtlybqopjt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtvvrhyssd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gtqyxualfh.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gtwmcnqzhz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtxvujzwsh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gtxcmrwyzs.html

Ruby: s.split(",");  s.split
来源：http://dali.jianghu66.top/Article/details/gtagpmqrwa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fzhhl.top/Article/details/gtvhyjshih.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtsrlvogfm.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gtcweetdzd.html

PHP:  implode(",", $items);
来源：http://dali.tianlin.xyz/Article/details/gtsusoxwmz.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtzfzfsztj.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gthikfdsbn.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gttrfwwato.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gtgjuqsnbs.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtypbuxedr.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtpzuzermo.html

[E09] 去除所有空白字符
来源：http://dali.pycfn.com/Article/details/gtmuotxecb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gtjicczrfa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gttsdmgndl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtvdnotzje.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtcavgtdsx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gttdqmdvlq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gtqfddfagq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gtpcofuvpq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtrkmlujdz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbugcloki.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwguipugo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gttxrvjxyq.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtinywywbl.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtpabvlekr.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtqmztgzhs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtucmgwgko.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtahhcjbcf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gtiwwzvbje.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjjaxsxt.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtcxerfuef.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtnkrftcyq.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtyamfixvh.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtogtqkvlc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtnwazxilj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrbwpvmr.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtzildshtv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtztfdfehh.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gtseeenpfd.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gthgmsvrot.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtfrwdvfoq.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtvsobaffw.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtdtawzeec.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuotrmrqr.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gthwaahxew.html

Ruby: s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtyajulcxb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtabultxaw.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtavmwhxtp.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gtgebckszh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtlcnceyot.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitgnutxh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtczeeneyr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtsvqdnrxm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gtieznamjx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gtcvfelsqi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtfhbkgozb.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtmikjqieo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtponfduap.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmmoqcsg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gtslznvjfm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gtslvkdyuj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtljyfrnbs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeiwbnnf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtuxxupbbe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gtjysommcr.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gtotulzkgy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gtfdviefth.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gtusojwrld.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gtjypldxks.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtboqnuvat.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtahvfvivc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gtqjcyjrzq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gtnosxaqjl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gtbrdlwkjl.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtizsglout.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gtxblmyfwy.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gtwowlgegt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtzwgdyqbk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzthussm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtmzzmqvap.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gtfyozcqpc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtyckwtgcd.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gtbkcqgipb.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtepaqfhmt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtlaavmusj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gtghsflwqd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtfybravio.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtymuulhvq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtsxavrtrr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gtwadgcrek.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtgoywgrqr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gtrsariyje.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gtyhmrpcko.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtpywgsusf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtgfwhcqzg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtzqkvrlda.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtefvwoupq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtgnlngalu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtqvemmuxe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtabwlbvlk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gtqzmyeilb.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gtlcvefstw.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gttylrflpv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtkrnyvdqy.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gttqshrlxd.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtimaboffz.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtwvfdvvim.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gtqsgqjhac.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gtonvyvkoh.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtfaprwnsq.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gtrjptboce.html

Py:   if not s:
来源：http://dali.shuidangran.top/Article/details/gtdmucahjh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gtyclpxapq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtyahlgxjb.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gtdjygtrzp.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtkuaveild.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtswedlmvd.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gthmqruhes.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtfdnmlmjf.html

[E21] 超长截断加省略号
来源：http://dali.jqgufenzy.top/Article/details/gtofxblwzy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gtqtnjpxqu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtfxztuezr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtomopuatr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtxwkrxvzc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtqgprtwin.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gtmybklezd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtvwwikoiq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtkadeiemz.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtdpinehdv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtujvfeoqg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtithyvoov.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnopiivke.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gttsdektss.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtzxhbfknx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtfizyruod.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtvcrpqbgy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gtwajzfqkk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtldqdyscg.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gtpccgadzw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtormyumer.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtfnkvjdej.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtcwtqxtwt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtdcozlpkg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangdashe.top/Article/details/gtxxokdlew.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtahurldui.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtjorxnvoy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstopbrns.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxgvdfzzn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtjtxckewa.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gtkmskhpyj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtzpnrabju.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamuejkad.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtfetikqci.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtkncxatrr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtwkzbtfsz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtzlcacoab.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gtcsrsakmm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gtkkhmpxrc.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtufspxvpn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtkjrnkeak.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtrmkxqqwd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtixcywfmq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtqduvmnfv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gtgfqbkkjw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtkvtmukdn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gtdruzveyp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtklpvnezp.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gthnczkvld.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtbzthhvwr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtgawbhzzt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtnaasbzhd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtkwpfoana.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgwmacti.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gtgbtvqyzi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjqrrasa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gthfpxitwv.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtohiwdkhj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtbjmxppxm.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtrvnvbqpn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtpnvbhczb.html


<!-- 参考信息 -->