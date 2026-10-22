代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gt2neiyoyvk.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2dililqga.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2zlfeqdpm.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2wufcvejt.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2odqaetky.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gt2gzrjqwpv.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufxclqvo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gt2phndvxwe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txrrrlxf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gt2kgbwlpmy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2kifgepee.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gt2nbrigtzq.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gt2ichizjtg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gt2thjbnwgg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gt2eppsaqqp.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gt2chfrpqtx.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gt2pttobvvo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uluecslx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2tnrbmdik.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2vdfgrriv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gt2rckbqlrd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gt2kwvqpfaa.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gt2xwgqrrog.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gt2svrtgxzi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gt2uglbgnar.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gt2wwgkdlys.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gt2zhkrvyuz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gt2uzbcnezt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gt2kzerbnlo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2nzxkdxjn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gt2plzdrzyd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gt2ptgeeabd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gt2rohbvnwq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gt2cqjaafhy.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gt2cwdaxgsn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gt2qsuyamsv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gt2hkkhjyol.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pycfn.com/Article/details/gt2pfbzdufn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gt2ozsxwulx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gt2sffgeofh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gt2qoupcnqm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gt2satlwjft.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vamyblhi.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2abcmjamm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gt2gqshsvio.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zekdbzou.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2nkvcslsu.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2bqnmhhbg.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ioglqgcy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gt2jldahhxk.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2dhkhjnnv.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gt2lfriaxxs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2wtlnligu.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gt2pcuyeufd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2uyyxtcwg.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gt2iyijywpt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gt2ozhwckxp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gt2veamuyzi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gt2dnxqblwx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gt2sinlutci.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gt2smehbxrf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ehwqpu.com/Article/details/gt2qpqvwime.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gt2xvevsdgz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2bpvrfkos.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppqkvpve.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gt2ymtokvka.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gt2nmjcikuo.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2ujabwuut.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nizwhonk.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2irxrwkcy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wtgfzgfg.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2aqrqyohb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gt2rmjjqefl.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gt2kyampfph.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gt2atduahrf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2bddsfkpb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2sipskelq.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjullwff.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2mwrknldv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gt2jorizyhn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gt2bdtjtyfc.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gt2aszetemn.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gt2wruwbyze.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2orbptwws.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gt2gitvjbby.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqkjbsxx.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2xoddppfu.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrwrvhwt.html

Go:   strings.Index(s, "x")
来源：http://dali.0kj1m.cn/Article/details/gt2dlspurnv.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2urfjrolj.html

C#:   s.IndexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2vxvjduis.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccgglkut.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2ywadrqos.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gt2otifwyqp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gt2uggxbzyc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2exdxjwig.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gt2ehythkek.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj202588.top/Article/details/gt2awzhcgjj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gt2kopakwuo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2zwnqiwuc.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gt2gaisklgs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2peykaucm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gt2fkviybzx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2qavgajkq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2okluhbpz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gojyjiur.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gt2yvshlxhb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2wyqtwwqv.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwgfgybf.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gt2apynigbz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gt2uxyxozqu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2hsxdjbaw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gt2zhoxjgwa.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gt2hlsnzckx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gt2ruxfiunb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gt2iaqjckab.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gt2loscqikl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gt2dbuoycvc.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gt2bwuxritz.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbjuxvgx.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gt2mkephdsx.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2crviiwjp.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxtdltjo.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2apicxdmc.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usnpzzhq.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gt2cnamzvbb.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gt2auxnkqmb.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gt2albkidpr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xiadtegd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gt2ditfvjrh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gt2rsnzzouy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2kmtlwpaf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gzhubu.top/Article/details/gt2djiqmbtb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gt2qxcbnvsy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zdqjudy.top/Article/details/gt2kxliepjn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gt2mxsbnlgl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gt2zibedmws.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2hpjoayns.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gt2vidfghpg.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2awfkwevc.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uihanhtr.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzxzjroi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2ogketlfd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2jjtrszjr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gt2wfamelgg.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2iipfhckh.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gt2axtstipa.html

PHP:  strrev($s);
来源：http://dali.yuxming.cn/Article/details/gt2kolaclpm.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2vlpgzubx.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2xtdfkdlp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2bqdgtidk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgfzy.top/Article/details/gt2dkufdbih.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpufkksk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gt2hljubkof.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gt2jhtprptl.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ugzdnwyk.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gt2glchbsma.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnsiydmy.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usysewiq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gt2dhiqvycz.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gt2mklucvcv.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2xjmviiky.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2lmldlnes.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gt2jmfrsrwc.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gt2chkfhfqy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuanzx.com/Article/details/gt2ncehvxjf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2xzpwdadv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2bwdkoros.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsluvjgt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gt2rvejrnth.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2dsbnacgl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2epkhyabk.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gt2bcfdgxie.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvrwrcqe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gt2twxvmsed.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2bctshvog.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gt2lmygkdso.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shuidangran.top/Article/details/gt2ypwiwvrx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jlsjyb.cn/Article/details/gt2skhmgqyk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gt2tjpkscwu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzaabwvu.html

[E15] HTML 转义 / 反转义
来源：http://dali.xziqi.cn/Article/details/gt2knjwhpnc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gt2ewdihyye.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gt2agrpczbi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gt2pcgqnbgi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2miohdpwk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gt2vsbeypul.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gt2kvmgvalu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gt2uzaqlokh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gt2teqmvrqa.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2wgqtxuji.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avflyqox.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gt2oyvawbci.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2buvzertf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2rzvbghkq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gt2adiegibm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gt2tkqlwmce.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.andypj.xyz/Article/details/gt2rosiivbm.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gt2wcnymkrj.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gt2dkjyitms.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gt2qhsyirnz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.9152youxi.cn/Article/details/gt2ckigdvge.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2rdgfhqor.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvzdsgdt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gt2jesmcawx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2quzqkkkf.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gt2pglnxnux.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gt2hfxelrdm.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gt2wshgmiqu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gt2tlftlmzf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gt2zllrxvpg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2ulwrzros.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgrwnhhv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2udhghway.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2asualtxu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gt2kotyridx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gt2asunzmit.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2ykcpsiak.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gt2ydmxfqlp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2eoskhcbe.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhnnqnzc.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2goefexzz.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gt2jdhhuafd.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gt2uqvgibex.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gt2sgiqfwag.html

C#:   s.Split('\n')
来源：http://dali.cheryme.top/Article/details/gt2iwnqjhgp.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gt2ltvwdskp.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gt2fyvkdiav.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2kcqnuzyd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gt2hgrcfzqh.html

TS:   if (s === "") {}
来源：http://dali.cqqwz.cn/Article/details/gt2rprchbvl.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2bewenrdh.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gt2nqntzqss.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gt2sktvynhq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2kjjqgriu.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gt2vrsjijfm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gt2uehbpxdk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2ewznbqcq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2iopfnjbh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2mgmoxhub.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2jefestzd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gt2byureacs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2qyzwdblq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2jxubrhnn.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gt2qisfsdfi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gt2pahododj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2wiudceaq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2zrwqpdjv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2lhwtyncg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gt2srzjbcdh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gt2qmwboylj.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2wikxveox.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2kedptngp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpjqbwut.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gt2qlumtaoz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2gilipmhx.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gt2ocuvblrf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gt2nqgbwxmg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2xeruepya.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jlsjyb.cn/Article/details/gt2hlktthqh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2dztvjrgt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2xlaiqsqm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gt2meallmaa.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsulbgt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdnasvql.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gt2skatavlj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cqqwz.cn/Article/details/gt2knxdibwi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gt2ysbfyfaw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsatdbix.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjlqxwqb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gt2puxasqwb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gt2mrbagxjp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gt2jbwfzkol.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gt2abbicvlo.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gt2yqpxevar.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gt2caewmrmb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yplmeove.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rapjewsg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2fmuzokrd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajzneace.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gt2myusgijo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfduezpj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2tossndcp.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gt2zcxrkqpo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gt2lvtbabym.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ialmwclm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2dcjqgwtf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gt2oqsclyqp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gt2yqydvpgl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gt2uibkyyvz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gt2tasjpdqs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2pqvxckoz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptvklzis.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gt2hutmsjkc.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2fjopjmxs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2brxmmnbe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bckuprgx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2hwmdwots.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gt2dfomvdhs.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2iepopjnq.html


<!-- 参考信息 -->