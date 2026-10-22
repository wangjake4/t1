代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umlvmcst.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gt2xsiwltvn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xylfe.cn/Article/details/gt2bnwtnnaf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2qesxvmwy.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gt2erlfyngl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2cyyxfzcw.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2euvjttyu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gt2hdtoehwn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gt2loqnlahd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwwkguhg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elezsqbd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gt2dztmleas.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdcixzgh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gt2inttexxj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gt2jgoemwgp.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gt2jnyzfltm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gt2daucvwmj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gt2jygyklrc.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gt2blvbroha.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2fjkfpggj.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmwxvfot.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvsjnacl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hogpinnr.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2ubnethie.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gt2owdbsbgd.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hoebkcqf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gt2wkxehxaa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gt2xbyzdawy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ksuztwvp.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2dyxpuirg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gt2wpglvicx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gt2elvredoo.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2nydrwavj.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2hiwuttqb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enwqamli.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2llmmfmso.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gt2pihxacsz.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmggydjf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gt2uiovvtxr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnpagdko.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gt2tqlwvpvd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gt2phabysss.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gt2bnwqlbua.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2doaljobp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2rwaujtuv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcyjlsci.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gt2csivcmpi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gt2gpgmnxip.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2zawdctsu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2vbszpwtf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2axrteety.html

[D06] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2bszpceop.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2dpdvvdsr.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gt2ilyoxeae.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gt2hrgawmwn.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drubpjmk.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsfkuyvr.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2jamhsvrg.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gt2zjsuhszt.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gt2oiwmfaqp.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gt2dtvhiykg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gt2bqlucehw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gt2ttsfmroc.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2xbtmuufz.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2rohydcdi.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2zvvlvrow.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gt2qukgoeth.html

Ruby: arr[1, 3]
来源：http://dali.jqgfzy.top/Article/details/gt2rxjygdyf.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2ypbzuepj.html

[D08] 合并两个数组
来源：http://dali.jqgufenzy.top/Article/details/gt2buvqraam.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gt2wjoauyod.html

PHP:  array_merge($a, $b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnlpkxqx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gt2fpsiygue.html

TS:   [...a, ...b];
来源：http://dali.hammf.cn/Article/details/gt2dnqouaco.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gt2bwgndohm.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gt2hgevmyiw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2etzabstu.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2iigwvrqo.html

[D09] 排序（升序）
来源：http://dali.gzhubu.top/Article/details/gt2ylrxglqp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2iiaomxcp.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gt2lpqnjtvg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258.top/Article/details/gt2djindljd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.kuanghao11.cn/Article/details/gt2yxymyitx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gt2xsfqfvbm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2kvyynbrk.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gt2lkpbblof.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gt2bznustnz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gt2loiuksck.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eoyruwvm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gt2scxukmcm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hffscxxg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbqvvodi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jyoumei.cn/Article/details/gt2pmihzfst.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gt2gfdoutuk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gt2llvazaay.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gt2dmexjoiy.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gt2xspzjkmu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hfpthk.cn/Article/details/gt2yjezefsr.html

PHP:  array_reverse($arr);
来源：http://dali.316326.xyz/Article/details/gt2fvlthzpu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gt2lssymkxz.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gt2ayxqymql.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gt2ahuhekgg.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gt2sehisvat.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2tvirujmq.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gt2rikgotgd.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gt2neeqvmkx.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2qormvepc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpxcaxmg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2rjicljtg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2ujxoyjnd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gt2lylqcbyn.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnzzolhg.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gt2prhtyzjh.html

C#:   list.IndexOf(x);
来源：http://dali.hammf.cn/Article/details/gt2hbitqyhu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2waezfbqi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2obvquhgu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gt2cpxeycfb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gt2euvugauj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2triqqtev.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2fdbctspx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gt2abuaqyhs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ppjwa.cn/Article/details/gt2hwlkicmr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynpvnlfa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gt2rxmaglcg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2gplyfrun.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gt2ujidpsar.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2kedbllkd.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gt2gbxitwnr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.316326.xyz/Article/details/gt2tdqgblyo.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2pvrmoxmh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2zlxhxnyw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2twsbauqp.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gt2uaahhkay.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gt2rfmimebc.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2pelsiikk.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2rnivxgsq.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyoqqgbw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gt2vlghkntp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gt2sqsoozin.html

Ruby: arr.uniq
来源：http://dali.jyoumei.cn/Article/details/gt2vzdoheol.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2xnyknzmo.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gt2wqgybinu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2rvyytwfi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trnogtbe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vpltuthv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2bacparcd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gt2hlghuojl.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gt2jbuduaiq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gt2yteuqfgy.html

C#:   list.Sum();  list.Average()
来源：http://dali.yongpay.top/Article/details/gt2qrnrzjis.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gt2pqhogiby.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2zgtibynu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2gqiilzdw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imvqtwzk.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2apmnwhiw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2hiysmuyz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2wlyrycic.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gt2baqhprwp.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2xidxgugn.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gt2slgzlcpy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gt2dmnxzhgt.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2gkckqcoz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqrmdsmg.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2gqkhidad.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2mkoloyxr.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gt2erzseyge.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijllonga.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2csptytzo.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gt2iqflbeha.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gt2dzmtoutp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gt2guwvhtds.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gt2illuuoqr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gt2uifjgqmp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gt2ljqboqpa.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gt2ijovijgq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gt2emtcqhzo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gt2ksqsievn.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gt2yeruydwp.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gt2qhwpycao.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gt2uhuaedja.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gt2ovztmycf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2txbfjgpc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gt2gpcjjpmx.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gt2ktumixgn.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gt2gjdeqghi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gt2wfdgcngr.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gt2zvvuspju.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gt2gyuaurkb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gt2ecqlyipz.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gt2qvsrdhyk.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2vmruzkvt.html

Java: list.contains(x)
来源：http://dali.316326.xyz/Article/details/gt2mtawdegd.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2ijmldtcp.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gt2gtfygcsq.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2yqljnmis.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gt2tcspvona.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gt2gomvgdgv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gt2rldcslag.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gt2dtudhlgs.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gt2yxvhvkuk.html

Java: new ArrayList<>(list);
来源：http://dali.cdnleiting.top/Article/details/gt2jppwsafb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gt2axdugpwt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2uboqnqre.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gt2vtcyevux.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvokjbxm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2kevecwdr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gt2vdjhuwpi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2ntbxympc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2feoxtfyi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gt2vnhwxmrx.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gt2lxupvjce.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gt2rcbesptb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gt2rbcojors.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzknexdu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gt2dtadxunl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gt2fazswadm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2uafpxglc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2dipzmygm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gt2rbbozmxt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gt2fzelpqvb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gt2xdheefel.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggaxrabz.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gt2nzwywlsq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gt2dpunwmfl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gt2nynsrmso.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xaxwbilc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gt2thgeiltf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcrngaci.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gt2virkwtpi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gt2cybdgwhb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2rerkgfxk.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gt2pdwyvhnt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyhqrojc.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2jpgkgpwv.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2zpgxbmos.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2crxvmhbo.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2pnklyvsz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2zpobldhv.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sputyejw.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2ysrwowqf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2pnusubsw.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gt2efffcchg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2zwdbzkbb.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2awqdacuj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gt2wqptzimf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrvfikty.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2xuzgmcvw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gt2mjiypjhy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcfbkwkv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gt2ddtmxhwh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gt2vtzwttjh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2iuynaknu.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcnndtrd.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2depijgih.html

PHP:  str_repeat("ab", 3);
来源：http://dali.meibo888.top/Article/details/gt2bhjzprxb.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gt2spegfwvm.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ducbemrq.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2osuqqtpe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aekoclaz.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gt2tlyykmgz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gt2ayihxqra.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2xsyblpue.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2bmnsdrqh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2viarbuqy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2uejndqhf.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gt2ncddtfqx.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2nwvvapkv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gt2lhuerlvs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gt2zohisaep.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gt2blltcnqo.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gt2ajuaqtfz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gt2pjxvauzs.html

PHP:  strpos($s, "x");
来源：http://dali.nwbrower.top/Article/details/gt2yboghgyy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gt2uactcqhc.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gt2ghwsrumn.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izjanlof.html

Go:   strings.Index(s, "x")
来源：http://dali.aibaodan.cn/Article/details/gt2knawriio.html

Ruby: s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imjxpswe.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2oecqtqvv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.havefunace.top/Article/details/gt2zixmofzp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2stoguwda.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenzaomai.com/Article/details/gt2ljnxfxen.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kkeqwfmc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gt2kgxlsaxz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uebvpzwl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gt2jnbrbxzm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2ocnusxdi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2hphuqduo.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gt2iafmwpwo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gt2sfdfhpzr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpnwozvc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2bwtqvnyc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2gklquymg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2xicukako.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2srjomxjq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2ykxempsl.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2otoqdvnq.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gt2nmrjrvzz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksugqzki.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2ebmwanyc.html


<!-- 参考信息 -->