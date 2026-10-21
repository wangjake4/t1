代发 wailian999

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtsnzollfg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthlxirggw.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtrfrgwoqa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtwdlhwqrh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gtieassbuy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gttkueofoe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtvgcpeebw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtmsugkesm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gteuczjywr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtziegbzab.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtyhsslrtu.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtizrkiyfs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtqosvdzbo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtruipueom.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gttkbdjctd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtdndpwnnx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtpfulqxsr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtzcwxgnjw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtjzayubzh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtfgkxoaas.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtqrvbcjpx.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtpynzdocv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gterbuzdbk.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gttwrraxfk.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtzxediwlj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtcmodxluo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtpdmfehun.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtwrsxepxy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsylqdqc.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtcuqlfrby.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gthxfttodm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtkqjfjwpy.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtsqfsduxx.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtsbwyfyln.html

Java: class MyException extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtibqjglib.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtocjftsvu.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gtswkddqou.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gtucxumtqg.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gtccuiitom.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtnromqfkz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtozfpewjm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtofgvcllo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtjdacptmg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gtyxxracjn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gtposwjfvb.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gtwsdtjubx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gtdbnjhejp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gtjvhnlbgm.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gtaxtsytap.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtgmhxsdct.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtdifzcdij.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtbgnhgsbr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpezdyuq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gtghtmobtg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gtiozrmqne.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtxpmdqfwx.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gtkiouista.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gturfkquhf.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtswnucuen.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtfxesrjrj.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtesqpezzu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sufxvd.cn/Article/details/gtczttnluk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gttvzknndy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gtwyfpyhwu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gteleppwzi.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gtuetyytyh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gtqjdzfoog.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtgjgwuqwj.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtdngacpkp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtboqrsjgy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtjaizxsos.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gtrfztqoqg.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gtewbhdhka.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gtzyessfsy.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtysxwrolx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtdhqwcpub.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtlrxfydie.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gtrngpcogi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtdagqygjb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gtmiqsylay.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtnthdwcat.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gtgcibjlld.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gttkdhcskd.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gttyiqzoog.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gtazxrvakg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gtajtnuxsp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtsjsoojmk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtxgbdszdf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtnrleoniz.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtfggrepbv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtlayttret.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gtsxtwpcyg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwdxjynhr.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtnsdalwub.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtngrnlroq.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gtqnfmdqji.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsornzyvc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gthfuyjgtv.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtcyqiqbcx.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtiavavqgm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gtbqqmptmh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gtiaysckri.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtdbvwzdtn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gtdljmyizs.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtyinsbfyo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtswqfrjya.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtathxypvt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gtyoujtoly.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtvpdifzxf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtfotfpenp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtfnbvxvcg.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtzlwzisbx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtwfrlgjug.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtdiqpdvwv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtjfxjthuh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gtitndoqxj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzheoqym.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gtbiojwmyt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gtuuvghbav.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtvrqruqsx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gtzelmumaa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtxtmwmbld.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gteapaswnm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazmftgqr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gteksepzej.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gthsbnkeqa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtwhmiinep.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtilxmyzia.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtkdtzzlvt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtcezyosog.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtgswysltk.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtneinlptv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtjaqdpnxi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtornsxvrv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtbzixdqyw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtbyuwippn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gtalqzsoqz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtuzofwcxx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtzcsrkdrx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gtrfpqcuzy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtvpgqylaa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtwjibfikr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gthzfmhxtn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehdsoncr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gthyjupvbe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtsgafqaxw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gttoxggipk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtmhnolyzp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtdvgwyodt.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gteufsbuqs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gttqstbjux.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtdsihbbbk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gtrgfagrlo.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtblqiuudj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtyqwigqew.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gtqcbmsoto.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtwzhfsvqs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtujgzaetn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gtduqguktj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrzkyqbh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtpeaksbui.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtioybevzi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtbbzfowgw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgxapslm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtcmnimtbt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gthwsggdgl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtvtcypzww.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtoypdeuat.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gttpickiuc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpernmieu.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtfbbhmbmn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gtjpdquhbj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtvwomdbqv.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtsimuzxrb.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtunolclmt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gtktmskbwz.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gteprxyqcv.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtaelwwwje.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gtahchdcuo.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gtzehxppzw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtlmwnyain.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtbucisupw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtpyogzrrw.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtjaedvjrk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gtbcjvwhht.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtyvmokpol.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtzkwjnpiy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gtpdpvzxcb.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtbpioboxx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtflmbwjoy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtfjnebbno.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtwmnjwuvc.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtwdgsglqq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtbqjuardd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtazwabfal.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtfykqoshw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gtnmqlghtp.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gtddjlpvcf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gtdflftwrd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gtsqpyyigp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtanumnvtv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gtxlmxaake.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtdkqhkymy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtwivskeri.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtljbzxudk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtacwzkhcz.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtfqvuqgsy.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gtzqmjgoet.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gtbgwxwgbc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtsbgbqujt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtxgtezhlv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtovooxdic.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtbswyilbo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtgpsvlzcz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtdftbqpvq.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gttdsnertx.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gtazuhnzbt.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gtikmqzakv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtbnrhbhrz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtfzhcanaq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gtyvlcishn.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtsvufyxaw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtkdhyhkkn.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymqdloyw.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtutpkihzv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgkctkxg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gtapgfffgx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtailiziuy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtrbzglocn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtmmgygbnx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtlpxgcvnz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtrlkvauwv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqsohxtc.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtwtdozptr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gtjrmwohjc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pycfn.com/Article/details/gtrhvmbrkg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gtsachormi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gttnjlbvwo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gtdnmbyilj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtetluxtms.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtscvyaspk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gtlxdgirqe.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtydbwaufn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gtxiqbptoz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtkymqzhlq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtqbsuatkt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtjzhfoipl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtxwnvirqb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gtxrmhqcnt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gtqnrtbdgw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gtwrzcmywj.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtxkkomwxy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuhmnozw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gtayoatcpo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtrjxtjcys.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtbylkamly.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gtuggrgpmj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gtukuwzhlk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gtamdvkxji.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtdixggsaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzntjbkiy.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtjsxjxibv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbkbjafga.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtlzoxswwp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gttbzipscb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtneznkrwn.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gthtosdyeg.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtsdizbkbo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtyzdsblvt.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gtfxrubpyr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gtkqydqdwi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtuvzuutfd.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gtgdnovjmr.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtxpxbngsc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtuvtfzouy.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtlecsmfrb.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtngcuflgy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtjzonimzj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtqjtszaqz.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtcdygnemj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdetzcgid.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gtdttikcpu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtdjgqnnwc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtkrzxatbs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtvzkspand.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtyrejupho.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtyuamoilc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtnixiudwm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtyfeygqth.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtsrurybgz.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gtqsqqurop.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtqqfebwtu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqgfwpix.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtgvhlmjwi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtbahhrfxt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtkscjgenc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtudxmjgyu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtdhjbdbhu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtqlopxlbn.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gtejooqhyv.html


<!-- 参考信息 -->