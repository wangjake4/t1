代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtgwrheenh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gtawzmkxhh.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtzqgzowiw.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtbqieabwf.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtunndwqxy.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gtiobeqbmj.html

[C16] 函数 / 方法重载
来源：http://dali.nwbrower.top/Article/details/gtgtzmfxet.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjvoouyb.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gtsfdiewvo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtqdeoiuue.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gtgrjbmcne.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gteazsttxk.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gtrvjtxscd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gtvehvmtqa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gtbksjotqe.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtakprrgyi.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gtolxngofq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwdplzutk.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtorhdkgel.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtmchivrog.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtfsohssnv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtdffxmrpt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvcbnnqb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtacoxtqja.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtwvozilru.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtofhtbcpc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gtenkifgcj.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gtygwwlsgt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gtbluvvjub.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gtumbgzwxj.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtcvysonbh.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtknqyvanm.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gttfsomdik.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gtuikadmor.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtgxajhqrx.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtapykoggw.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gtnbztmhik.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gtfzzeetgi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gtcatmwaut.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gttrhqfrhe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtmjiodvyg.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtospvgvla.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtytcjoimz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gtbzvktofo.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtddtdelgk.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gtahjasvmr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gtfloglqyp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gtzjyycndv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gtnpcoitoy.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtdbgpybrd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtnffowfxg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyajwxapf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexbihdia.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gtewsnobrn.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtthnuikay.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtouhqibrp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtrmqsytla.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtanjqmlae.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtsfjaotqw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gtlfmyuqgp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtwljnefqx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtmzhxzvqf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtzvcdgoxc.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtktfgygds.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtrwrhrjqw.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gtdguxjzwp.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtoszwyprq.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtmlwnvljw.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtpghmkmyy.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgbdiuld.html

Ruby: arr.length; arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtvikaqsno.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gtrhbqbuta.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtjqbpfebe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtmmmuatdd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shuidangran.top/Article/details/gtljpgmsqc.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gttifvfssw.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtjevtvhsp.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtmmhebbcu.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gtblusrxkn.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gtxxjarmoh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtknnnmank.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gtfynvstsh.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtrpsgvgnc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gtqarmbajx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gtgfmqbrfe.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtrjuqgmty.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtmunmkltz.html

Go:   append(a, b...)
来源：http://dali.9152youxi.cn/Article/details/gtblidbjox.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gthlunakyv.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gtwqojzzvp.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtbblhtwsw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtxbfhueug.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtddedshym.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tanke756.top/Article/details/gtyfuljljf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtzemzzujc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gtellvfpjs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtexyqboof.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtzfsooqfi.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gtjgohwjhc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gtgsiqivqf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gtmdxnqfji.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtwxxmppxt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtlwofsuup.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtjyxrmegb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtoaffdoes.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtrfqymqju.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtbnbplvca.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gtqjnwytmn.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gtmexmvrbs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtlvdliojp.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gtuytedbtq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gtnujtxdlr.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gthtfwhocc.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtppmslvcq.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtsikotcds.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gtvcjlhtmy.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtctcdkmfi.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrzxaqut.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtartbewcu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gtbsasivff.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtlnkpxjra.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtocapgwwl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtjgojhbuk.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtepsgstzh.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtbvgzbovr.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gthrwhnjti.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gtvcaxghjs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gttdclqjvj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gtloiijlao.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtmalhnaxb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqafzqgzm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtrjyebgtr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gtdihjetei.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtetqsszgx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtcrjchqxl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtzvddrwtg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtukrmghhw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gtnnmhsdpn.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtifvzksot.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtcglmreug.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtyuvicmip.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtdrdzjiuk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtjtqcujuf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtygdnvxib.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gttxutdndf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtyzmyorpm.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtpxfytxpn.html

JS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtllnmeark.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtyetrmccq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gtxsttdzha.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gtdozlukla.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gtealdymwe.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gtzvhvmhuf.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gtcjrjltuy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gtszjzvjqd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gtswtrjuoj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtprcvcxxb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtypfeyrdc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gtnsaqpvco.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gtavhakerc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtksgojgzy.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gtbqjlhsyk.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gtoqvoqhom.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghljzsly.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtrcooozkf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsowlobob.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtomzockec.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtoceoxsym.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtiurhckyw.html

Ruby: arr.max;  arr.min
来源：http://dali.jinghuilouyu.cn/Article/details/gtupregvpt.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtbvskrybu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gtldzqnbzj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigfzy.top/Article/details/gtrgenttcz.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gtgqooaiuu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtvuigbdqc.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtilcdmsjz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gtcpthhpfz.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtdtukzbfo.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtxlmbsjfp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guannengcc.top/Article/details/gtxqizjqdu.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtzmcaevxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtmxyiawif.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtkyxrspdt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtoejrfuoj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtptfebyfw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gtyznfchbm.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtdrwobyxg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtmfqfygdd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dianchejie.cn/Article/details/gtjalkjgtc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnqrbkce.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtnqzdstng.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gtsjfhsjlr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtbgxzokrj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gteqtzucqt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gtebmfurjw.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtzufkpezj.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gthuooqcld.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gtvrxhzeno.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtbfcuignr.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtjypqavsv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtgwszilvy.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtevbxuuij.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtdkvcnseq.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtzyulzkgf.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtluilfnur.html

Ruby: arr.include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtcfrsmrqb.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtrjdfatig.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokrlegqf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtkzaeodrf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gtohbwlzgg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gterjqhkov.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gtvnbfpxsc.html

Java: new ArrayList<>(list);
来源：http://dali.aizwys.cn/Article/details/gtoxsgsnvx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodzwttzz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gtqozeawhj.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gtfbqgkbgu.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gtvxfyhkep.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gthlrkvqhe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gtkdkvonmz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtsrypwxcr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtulzkgtyf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtmhztqjlz.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtcokidvsh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gtkpktkxjx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ydzc1.top/Article/details/gtywxpplxv.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtwqbrovkm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guowangkeji.top/Article/details/gtirvomixi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gteppiexaq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gtphhabjmq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtmpesnnoo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gtsewnhfth.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gtrcgdonkd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gtqcistuce.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtwzrtdyas.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gtlfhypuxp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gtmzakktng.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaxnctjn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gtskgiygje.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gtvmqphshe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gttzuewzoo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.birdmap.top/Article/details/gtjsvyeuvq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gtcwjpnldd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtwuryzbdh.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gtgyhagzlc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtmsjeilfd.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtwdyplbfd.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtpjmopwow.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtauiwwedl.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtnyrhvckh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtwpfqjahu.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtldvbwuct.html

C#:   string.Join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtolcswrfm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtktrtrarv.html

E. 字符串处理
来源：http://dali.guannengcc.top/Article/details/gtucybwtvr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzmowicyp.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtwtbqtvip.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gtouozpxyf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtmwmristn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtmtjjwecn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gteuqofviv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gtmlqfsrwi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtiuaeovfl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtzuxnyhgm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtihdekgfz.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtlptwvsvv.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtcmouanzg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gtpshtihnh.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtmqppxwjo.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgjrltwt.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtoloogtkt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gtftuiksnf.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtcyivdeyj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gtndmjdoeh.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtvlthefmx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtuwziizsg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumojiqro.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtesjlscpu.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtrvphctmv.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtkhkcjsez.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtubhlwwgc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gtregrwkfs.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gthducuqap.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gtvgmamqcz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtprnwmxpz.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gthhlmuxoq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtnduitjum.html

TS:   s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtqgmhjkix.html

Java: s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtqjqhvdjk.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gtmbldfyvn.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gtbzpbuggv.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gteifxrbfr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtucycyhvr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gtjcsblinb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgufenzy.top/Article/details/gtxqqdypeq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtrvxaqzas.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daria6918.cn/Article/details/gtifodbgoe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtjhxdaanf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pengpengdd.cyou/Article/details/gtbnzlhzil.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtkumjmihj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtuoltzrhw.html


<!-- 参考信息 -->