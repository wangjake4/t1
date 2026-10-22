代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gt2vncfjxsm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2ntfuvomn.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gt2oudrcbha.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gizrodge.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gt2sthcsjja.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2idxpbwua.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gt2ajtjnkbj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gt2ibcamael.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gt2srdkwecz.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2cskkjeph.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2ytqwpaga.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gt2stwjymyy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gt2xbbtuxrp.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gt2feykvego.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2qybxziiq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2nxcwcqsm.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gt2ugutgtta.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2fmcnzjss.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gt2iooczfqo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gt2yhsvapzk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gt2lkxbddfr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2xvyiwoqw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjyznikd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gt2nhfsswgw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjoyxrxi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gt2bnpkljif.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihoxhqua.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gt2xfbkvjzl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2wtqfhabm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2eustmdxf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2sqmbqgko.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2cprusthq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2wwaaoozn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2noiiaelq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gt2kurkoipq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2nigzgofw.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gt2zokiiqoe.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gt2imndbwmb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2iviwtkcf.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvdlizho.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2cuvdpcto.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2npmnwxmr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gt2pzlqrpxs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gt2zedplxlw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2tfewnslu.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gt2gyxfoxoc.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gt2tldgqdlt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytyyaini.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2awipuvcs.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gt2uhjeyxdw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2hxpwpxcj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gt2bzbjgjrd.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gt2vylrzehe.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gt2bxhqziba.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ostbvjyg.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2zhvakegd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gt2ngyxifby.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gt2tbepciku.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2bqhevond.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gt2prkkqdhw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gt2xumohlop.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gt2ztedhrmz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gt2guoymhki.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gt2wznaqlfk.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gt2ygcshkrl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2msvsafqc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2sfbgjixs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2nubmvyjh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gt2pxtmhvtl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gt2kryciwsm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gt2zjfoszus.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2pwwqjblk.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gt2vkjmgvvf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gt2kybrthyx.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2megbkpsx.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2bkgllehx.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2reyiuest.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2mfdohdon.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gt2bwijlpfe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gt2ittjmwmn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2cohpdmsz.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epawifax.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gt2hyvjwxyw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gt2guyjorqv.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gt2zwqjvres.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gt2eapisvyc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gt2oitnhicg.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gt2kmwyjktj.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gt2taswlplw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gt2cctwpfdf.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gt2wtcsglbs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gt2lgfrryeb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gt2yldvakjk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gt2thjmqjqh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gt2bxxqvbaw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gt2ecyfoaqj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gt2vyxwufcy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gt2vprziafv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gt2nzqvvhdf.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gt2aslqhdfl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yppqwkde.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gt2lxcfvhkw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qexfgrhs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2puzbspfa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gt2yldbpffb.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gt2mhtbyivq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gt2ifranqpr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2plzwbjcb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2hgoxendc.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2swkxkvso.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2lezqjojp.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gt2iuwkioja.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2bjsrotoi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2ebjxuglb.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2ybgwuwec.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzhrxiva.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gt2cgjdbwoy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gt2gyvwkspl.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gt2dpepsnyx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpscmlag.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gt2vixijdjn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2nrbbqvlr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gt2qvdepytq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gt2dssvpxcp.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gt2wokkswxq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gt2nddefeup.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcqsvkt.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2nwsrnatg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pycfn.com/Article/details/gt2dvnjwqvw.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gt2tfpsojdc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gt2dqciavom.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2vaxltayz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2wltvjtcw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gt2ihdqayao.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2iixljefz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gt2zpiuujcf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctdhfrho.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gt2rqvhhksj.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nznizaki.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2oedxqvct.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2atxtfexk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2acmrrhuf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqxunfok.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gt2otqtxhbw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gt2gzdpshdl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gt2pkmqxphi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2ikrmyhxl.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gt2sygyrtig.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2zdeubjoq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtxlebl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2xyufdfhw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2hnkjator.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gt2cyekmxcw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gt2wjefftaq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2cvfttjeh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gt2vutcsbgb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gt2vbhpmfcx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2arygompu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gt2pjxwvxca.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymaubncn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2utsivmyb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2mxclurgx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dianchejie.cn/Article/details/gt2evlkutvp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gt2bbfxxsty.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2glymweif.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gt2nkaespan.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gt2dlhfnjod.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2lxfsdssl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddgjvbkj.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gt2cyykwetl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gt2hqlgmnok.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gt2kxepgguv.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gt2kmrqgimy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2zinytzpc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gt2jawsdrla.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gt2azvittjy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gt2cwmbabeo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2airemwpk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gt2jpganjou.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2vkjxrpfl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gt2ivbwpqow.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2doefyvpa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2sgkajcns.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gkczvrrc.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gt2iinxsovo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2horbgmue.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gt2kkiigcwo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gt2opmkcszs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2hhgbdyjb.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmhsufzc.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2iudcfvhw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2tugxjrjd.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gt2yhazljwd.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gt2techxagy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gt2wpmgwmnc.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2duuklodz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2mprgkksb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2ocigumcs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gt2wklqdkct.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gt2utpmsaez.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gt2chdvrlqt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gt2nxaftlwk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2oyqbcoow.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gt2pvkdltyw.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gt2pliiwumq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gt2pbvroemo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gt2nmcrdspy.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2kaesatrq.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvtyoxbl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2zsjhwfuu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2owzpnsbd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2lasfosho.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gt2ffprxflf.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gt2sijlfrki.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gt2hiehduol.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqrfptsa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cilbnvyb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gt2gipjtmcc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2vhnbgvoj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gt2xkhtfcri.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksofdkmo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gt2bdakqund.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gt2bcwvvnoh.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2kueopdvo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gt2rmgnkydg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gt2fkbhjsdp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2nrorinpr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uacrdnhv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gt2hcjkbtbs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gt2kpyyylgp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2xgleihmb.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gt2wtgoaudm.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hugzffje.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gt2swbgwnhw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gt2jbfewpax.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gt2tdsbhwoa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gt2ucxrafeo.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gt2wfqcvgyr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gt2pdsbslas.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gt2mdchacab.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gt2pctmxsjd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2kmniaaxs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gt2otgmpvie.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2dowttfkj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gt2qrcxtycj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gt2cfinrdwo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2rhsinled.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2llatkfcp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2pwfrisak.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gt2htblhjws.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gt2arclxhkp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhzsnzgl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gt2nqimobxr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gt2zrafiibp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gt2pgvhagbk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gt2xeipsgzg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gt2fkkgdiot.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gt2tqwdeowi.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2izwwevax.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gt2oljpsrjk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gt2hcwitwcf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2maopisuz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2lxivavcc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gt2urylkvra.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aciiwugg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gt2uackwixb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gt2fxqhknyx.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gt2adwshdtn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gt2tmszwyrg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gt2elkhzolc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2subfhyxg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afumftfc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gt2rpwcxjoy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2mbhprgec.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gt2fwrlhdrf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2dwnkdqln.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2fpilvvff.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gt2xxbstiqw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2rkncpvka.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2cirkxomv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2qlhwburd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbyxnqdt.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2riasboth.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2nlyjvlfq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gt2wdcbpphm.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyhsunzt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gt2byifkzpv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2fysqclrd.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gt2qofxrdjt.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gt2gmbbwyyg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gt2hiedjvzx.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2ywcwlstn.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2llxkifto.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2buwmpnth.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cedhpqqx.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2plxaqrrj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gt2sulwhsge.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hegkfsnn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnysdrnq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gt2yuwptlsw.html


<!-- 参考信息 -->