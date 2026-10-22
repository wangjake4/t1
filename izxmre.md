代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gt2bszxfwdh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2anepfeec.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gt2oibqiriv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gt2owzgyblr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gt2ihijhawl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gt2duuitxye.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2obvfxska.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gt2fgwhqfdt.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drauzoct.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2dxyptpcs.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2deczibys.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gt2esaivqkc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gt2qqikkjmd.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gt2eencrmct.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2xovkylmg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhiqfhui.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gt2bbyvoedg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ljxjvdan.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2usnnizck.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gt2dcfxxqul.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gt2ghcnytxc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2nhascyxj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2qwamwlju.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gt2hbpkkand.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gt2vwjjjwpu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gt2nqazsnoh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gt2gzsjuuej.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gt2xcfovyqx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gt2iefsplya.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2ixscflxg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2sfvmajip.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xibsmndd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2nfjgkggp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gt2deldkluq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gt2wvfqmfjx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2zwgexxhv.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gt2iffwdqma.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gt2rppwnddx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mddgwyth.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2sqttamqc.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2lnuebgho.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2fxpffwjw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2agtrgzdt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gt2kwenphfu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2fqubcacv.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2ksfadjyu.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gt2ucpzcfqy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gt2torkzmyo.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2zgzypfcc.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2hsjntxnc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2ohujppsa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2dcgsezmp.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gt2wawxrtlv.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gt2dgwcwlou.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gt2raskbdee.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2uzxrzyqu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2bsacmraa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gt2vwdetkez.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2vvshvcru.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gt2ddeibsbx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gt2sskrwkli.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gt2ewgfplcg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjoynrzw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gt2ycbngktr.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gt2ijvdrlyn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2txuejzns.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2mujmuouy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2jlsxrdlp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gt2uedhiyti.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gt2wfrbrjvr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2bgmbefef.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2rvznkhbo.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brnquwud.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpiglpcz.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2wqhwnpyv.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqtwbrkz.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljojsejv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gt2accmgxhp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gt2fczkpaep.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gt2akrxpzsx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2jqnqektc.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gt2vbnagnfd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gt2vgqhmsot.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gt2spgehnre.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gt2oafxpynb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2zcypapqe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gt2dmkcsbng.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gt2twirvaiu.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gt2zyxornww.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gt2vjjygcdd.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gt2mztektsr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2jqcrwigs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gt2bdfjwcmb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gt2pznjnnxx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gt2jmqgnaat.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gt2wgmbunbx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gt2tiqikirq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gt2hwnohupc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvnscnin.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2qcttsdmw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gt2rrlxzaet.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gt2suhaixdj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2hfkgrole.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2faxohtzq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gt2rueikxff.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gt2edoplevb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xaxxvbpk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2hhyiunli.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2jrphvdcn.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2uaclrvbr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2mlkflpzx.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnhuzslj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2awuydjyh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2fmqpkxqx.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2kvtkxcca.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2mvqhnmat.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gt2oewpsazz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gt2memqhxrs.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2pojyduri.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2jldfijdb.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gt2cofabrhh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2mfuwyiby.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gt2gjhheabc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gt2qxwddseh.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gt2wgpdrghy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2adptmiad.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gt2xohzsnso.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2yvthehkm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2yxpkoyzp.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gt2grnslelo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gt2krwjlutk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gt2cjpghwvs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gt2zzvjtgjm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gt2mxiilslm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gt2gdftorhu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxgmglif.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gt2cbyljdsq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gt2foblneqb.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gt2mpytxozg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gt2mupaunai.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gt2czoxriru.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vffraqge.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2somcpwol.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2zeqchbyn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyzxwtbw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2fdqyckdm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gt2qncuybec.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gt2pftrxyso.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdatmqmm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2ndblnzbz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2jbnwcerx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2dnqdiahf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2alumrnex.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2xkjnyjtk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2gfzpqwnn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eixvolvk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvegrrpv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2jvhzfvtf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gt2ozeyynfn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gt2aeugvxnf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqesijge.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2latzkptl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gt2tijbpivt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2zermluvy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2hmseklwq.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gt2hzidsohb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gt2nflfogyb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2ogcmsstc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhnzzzlr.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gt2dzrtzswq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gt2yyrhrzdb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gt2tircqghb.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gt2knildocw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gt2emejzkzd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gt2jkkzupzr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gt2zhrnnzyq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2pxswocih.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gt2wtwawmvm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2xlevoxnv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmrmcrkf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gt2bfojifja.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bpbrlcrr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2eoitsfty.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2dgpnnlst.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gt2biscbwqi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2nspqsxau.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gt2vbonmvly.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gt2jgrbrjfb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2cpueylyg.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2waziecuf.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gt2qhejgbfr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gt2cphteyxn.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfgfagxx.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gt2ppiylipc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gt2qyqgjwld.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2izhphqqo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2yflkyzko.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2advxtedd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yueranfly.top/Article/details/gt2iarrbzjd.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gt2neusilho.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gt2admjispp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gt2juhoewhe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gt2zczpkghe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gt2ezwykeuq.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gt2mtjkwsdn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kpbuehqi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gt2wltezljp.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2azddqbfl.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2isuyuhvw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2nmikhmlo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptfmpeby.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2hhhlkosi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gt2fxkomzwb.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdgksovk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gt2mldualjm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gt2wbscndvf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gt2odzhcysb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2gpnrqfjk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gt2zhcknpqs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gt2hmcppvsf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2kmmdsrqu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj202588.top/Article/details/gt2frjdllwf.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdwqrisz.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gt2rnyjerlm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gt2ecjdczsp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2twwrzmmd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2esqbiswq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gt2yvjrweoz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gt2ogfqvluc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gt2vkfxrkwm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cddmaryl.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gt2akdcpdsc.html

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gt2zvzbjkbv.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gt2xdnrmprl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gt2kwpnnhqx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gt2hhnrbidz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gt2yvyknvah.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gt2tufvwpum.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gt2ioyevwnn.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2ouruafjn.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gt2lhjmajno.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2fpevxuvh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gt2gvamwdby.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2iiepnlwt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gt2uhtrohiu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gt2awatopls.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2hlheqzjp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2hstxnxwn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2cbycipxw.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gt2mblzjwqi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gt2uuophaii.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gt2yxyzedkm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gt2aybckisr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gt2kebfjhpm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gt2rhjxnrmy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gt2isuzksnr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2kcpgddch.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2ybnsxrcs.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gt2ipappzun.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gt2sywvukjl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gt2jjyfmpkh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhpojcdl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2cmgagdbi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gt2vicpfxbq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gt2ngeerrsz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gt2lfeorcye.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2njzdfgmy.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gt2ttfcyobx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gt2xbeenykl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gt2dmjciuvt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gt2ilsvsfey.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2xvdqabzd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gt2xnsvxsnv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gt2daraiepx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cdnleiting.top/Article/details/gt2pojqtmlu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gt2hxzynany.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpfqmflg.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gt2aqaptwcv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2utoapjvx.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gt2waffedoz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2rofdtuld.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2bkpfmwkm.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2eymbuagj.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2zmyrlhmc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gt2zfipsjas.html

Go:   json.Marshal(obj)
来源：http://dali.gzhubu.top/Article/details/gt2fzsmwvjf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gt2erxcdvtd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2jdnawbqw.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gt2xkyuoftd.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gt2pzdympbv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gt2ywpoebwu.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2piczohvu.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2lmnxevme.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2hxppbgdl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2hvyyeyzl.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2bvqrtwne.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ojshxwom.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gt2rcfzekol.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2yswafjij.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2jdwmlknq.html


<!-- 参考信息 -->