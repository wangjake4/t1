代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2odrahbie.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gt2xrtmfvoi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ytleeecl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gt2gtjdcunw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gt2yxxedyex.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2jutstmde.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gt2jpoqdmso.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gt2cabsantk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2hxhijuyy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2kaxjaazm.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gt2ejqufomn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gt2hhmodevu.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gt2uwefapmd.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2loamspne.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2bynahoji.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gt2tsigprpw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gt2yyhevddl.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gt2dbsmbifm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2iztypmlv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xvmekaet.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gt2wyvfiwbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfmlsjn.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2gcalwxrs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gt2ojgriian.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gt2shjptrmc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2ooesassi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2sblhcwcp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gt2ckbgtaue.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gt2skdagqqg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gt2ajmsszmc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gt2ywoiktea.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gt2mtrsvjpm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gt2nfkfdvpf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2crzgnzln.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2drytdxrr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2nlwxpfiw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2ggjsxgcm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gt2cumqpitx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gt2fmvvjqgg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2vuawqjif.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gt2fnhvffxs.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjcwdfkj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2gxqavjes.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2eoydipmv.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2etjltzng.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2ocbekcuo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gt2zsenexgb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gt2bqvdlnbj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2kkngsfvu.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gt2tglreigk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtzfaeon.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2bkrkhvjw.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gt2vbvcumvm.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gt2knzpygnd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2cntlvzpo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2cqsgxxzl.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gt2rrlfdmyx.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gt2eadbknpr.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gt2wshgurib.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2bfcdudpz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gt2gsnbfwgn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2yrvlsrvv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2bebbnxrq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2uqktrsol.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gt2uztxpagz.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gt2uhpwcfnv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gt2znchjaou.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gt2cbnaqebo.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gt2idozwtyq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcfklfnn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2fpmmghow.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbteyqjb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gt2awmlpzsu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxznesln.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzsfyfal.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2zrleouhg.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gt2fhviwszw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnqzz.top/Article/details/gt2vsvitjpb.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2ymaeqyzr.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2qseisirr.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2xlxpkjzu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gt2dxufettk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2fspumsjy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gt2pyicgsbw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2neovdage.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2gposdwcm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gt2mupoufii.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gt2mubxzsxr.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gt2gzmiyecb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gt2fzjyehns.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gt2zlrifxsd.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gt2pvowlomp.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gt2leixgzzu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gt2ufyyphkj.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gt2khqftepe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhvhmsza.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigufen.top/Article/details/gt2jahropsb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gt2crvlasqf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yonumen.top/Article/details/gt2vumvaaik.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixbvzrba.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gt2xxlreczu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gt2fmqpnhgb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crdpujrr.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gebjwynm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gt2nlxajjov.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gt2vccltruo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gt2gxlgimkw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2rwiezlit.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gt2cacitigy.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gt2ketbxfqe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gt2neywgctu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdgzylgt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2wuvybhsm.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gt2cyjcbaug.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2qrbonrbs.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gt2ydmpmzfo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2ibvldiaf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2zylvaiem.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2mjtvirhd.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2cithycbu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gt2vnzotwjs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gt2vswjeggp.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2lgymhkwz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tykhctwb.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gt2jseeqxxo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhjkrzxj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gt2gsjrujwa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gt2pwulpnoh.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gt2gkvhweig.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gt2zoxnsnda.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2qvumcrbh.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2njvcmrju.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2tectbgod.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gt2sorlkwbn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2yzhodavw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gt2zlzxrlex.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gt2oceoeljx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcvpwzsf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zisqjhkv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gt2xelgmnsu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gt2rxhwihno.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gt2jvyyyrhz.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gt2xonrliwu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2lxhnxsaw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gt2iyrutige.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2efasnogp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2rqnbnocn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2pwkmedsm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2umptkkyt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gt2ttichibr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2ycdtchco.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhmreqcy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gt2hbgizbgc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2kferldzw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gt2trqercdl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2nfexysxx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2cnbdszhc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2agepqyuc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2hnrfgsjr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gt2ppdnlqlm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gt2cchfzjck.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2hypdropw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gt2fesufwvq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2rgouxdmg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2hedyyejh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2uldkvcjs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gt2zajbvbjr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2xiifqybj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2qewfwfwf.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gt2bxjmhkbc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gt2blzngcdl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2etfxfjao.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gt2uoyrvqnp.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gt2zjgqlhhd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gt2wdpymnyn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gt2pnhqzfcb.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gt2vsmktztr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gt2oawdjvqe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gt2muhceica.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gt2tyjssoem.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2zivqilbn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2gfojieoe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqstiswc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2hirfttap.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gt2ghgsprhv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gt2wmxbardb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2kwvunktg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2nlhrxmgs.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2thvuhvlu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2plgtlcae.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2bpkyklvm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2mjtgvult.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2aylcdnms.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2yrjcxbrb.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2juksmmog.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gt2isvdwdqu.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gt2swyimafv.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gt2myrlnvia.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gt2sqtdpcxq.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gt2rwbfdlxq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2zuczkvsc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2pjpktuxq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gt2asatsiyb.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gt2ayfgxerd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gt2sncaupzm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gt2urggpqnb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2ihzdrbbf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gt2drfnazoa.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gt2hqiirclf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gt2gjqycjyy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gt2wadbquge.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2fydofkpy.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2pbcwnzcr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2fmeznwoo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2sbutauff.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2hzbrudxo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gt2xmlkcuyj.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2hioyykww.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gt2avszuekj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gt2lypafiqs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2aukwrnhg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gt2oftwynyn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2rpkodbdf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2wulcislb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gt2kccsploe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gt2idrgjalg.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gt2kgdrtrlx.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gt2dlwmopet.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gt2ipxxwbeb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2kqjwnjhk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gt2ivpcpcnp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2bajzwfea.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gt2mxjwzegx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gt2zfbdvulu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gt2zpotieeu.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gt2srpssvob.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gt2stizfwnf.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gt2lfbrmzba.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gt2sfxanthi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gt2ivxzctgp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtvgqdsm.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gt2aewjqxqq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gt2ebtlbjoz.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gt2jmwppqzi.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gt2cokcyqpm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2kmiltweg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gt2gudbyhvm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2zsshqlnd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gt2apmbmtxf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gt2xshdilkf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ichwqrac.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kblvpcxg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2armvtjkp.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuqpsapk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjrewjjl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gt2cxqpkdzx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gt2jdzpnakl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dufeetzv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gt2kvqtsalc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gt2fkpqolqj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xekhaane.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gt2qyevkvim.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gt2etjjauay.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gt2dhkrtpls.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gt2isfzzatd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2yreqgkqt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gt2kuhqhqbo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gt2fkjrsssz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gt2gowuqyfs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gt2ytepmuff.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gt2kvlzjfmm.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gt2zxpunzga.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gt2llpuniyd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gt2jzerkbom.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gt2ttylnbil.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2oxzmrojf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2knpwooul.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gt2mmevvgjl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gt2tzlcoojs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2ldzmjxwf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bhwzfvyh.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gt2ysqeadnh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eujhjobo.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gt2xxoxjfkz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbhmelvz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2rjeasavc.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2nfixeyry.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2ldhidlgg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gt2dkhiourf.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjjufxpa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gt2ebnwpeif.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gt2ujztiasp.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gt2qlkgeqwy.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gt2ssfqqoex.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gt2aesxspvu.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2loqzrvkb.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ujueaajw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gt2odzmvvjd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2xsvxfqjv.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2hvtpaxaw.html


<!-- 参考信息 -->