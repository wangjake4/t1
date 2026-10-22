代发 wailian999

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtfwspcgwp.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtdvzvebwi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtyvxpdrzv.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gttpsyvdcg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtstetcizl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtspkimbdk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gtzugwtxpv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gtnkuoddhs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtdddjxlar.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtnuettxbj.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtlopwnqtx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtkoulnevt.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtgjkxnuiw.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtiomryubj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtzwowmwuc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtgoeccxwj.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gtepawnlct.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtqxqccqle.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gthxlccavb.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtvthlbmdo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gtobvmcqxe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtiqacjlen.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtuhfhqmic.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtdpgyclqa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gtoocqnxhj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gtrgooowve.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtndgkhnam.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gtduqsiyhc.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtdswelfcs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtrkjjndpy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtqapvskwq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtnlcarisj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtzptlcvpe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gtatardbwm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtgmnugsye.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtmtmydqgl.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtmzkfpqyp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtmcxkbwvi.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtbqnwzhjf.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtggxohlga.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtlxxaiocb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtvjcplljv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gtipzweguw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwffztuai.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtpzpnazyn.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtqdrjfqnt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gtowlntdbh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtbgzwitrw.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gtfafdcfdv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gtytcbgrec.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gtgpejftbi.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtxrebzxyx.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gtjydncwtq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtcdtwmpcb.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtirglwtje.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtmhylxxdk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gtikquvcwg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtrgnfupeh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gthdwcjjln.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gtsfojxtnm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gtqdvaueha.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtrgvjfjzb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtiiigshty.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gtustslqjp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtizospvix.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gtitpkydgg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtkwjzkd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtkkjyqmgg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtsdqwdfcr.html

Go:   defer f.Close()
来源：http://dali.guowangkeji.top/Article/details/gtbtjvymmy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gtehjasdkc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtogxkqhzz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpxpxlavd.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gtwfoiyczt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtripbfkeg.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtisalvawl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtwzvjnigu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtwcqlabkm.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtstpdnaub.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtocfumctv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtqcxxutee.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gtiskzkmyd.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtdjuriqrv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtzmrjpoin.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtduuprsya.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtdfhrdhib.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtyfsxdhbj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gtgalpuoxm.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtredtgtdy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtqqkpfsoe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtyigexqif.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtaknomqhj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtlbmasddh.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtqjojixow.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtfnmqmqap.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gtgiaufjyk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhongyouzk.top/Article/details/gthftzcvyl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtcszizdva.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gtsfibdfat.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gtucwqdnrh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtzfoflggp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gtgrilamlp.html

[I04] 正则替换
来源：http://dali.zhengqikj.top/Article/details/gtqgvurhmm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtaxyqikgp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtvdascsig.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtkaibgehz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtlipgoszr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtoaonppia.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gtrvqrgzzf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gtfohjaalm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtxbtqnrao.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gtrqdcvlbb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtykswveko.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gtunvnnmta.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtflbqihkk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtuckaahma.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtgzqakuyi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtuttloqna.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtubkkzgrv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtobbquflz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gtiedhritk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtqofariwn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtrhxeytgh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtazcxoekw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtcluggzdm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcxajmcp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gtubgafesg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gtrxdzylyb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtqqlkhwfu.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulqjfjkp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtrdenbxyn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtgrmxduup.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtmhxtqfpk.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtmpngmcfn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gtkahjhsuq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhongyouzk.top/Article/details/gtslbanvhf.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gtnyaukpwy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtpnayghbt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gtboqehajt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtmlajqdyv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtqumgtrzg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtneknujij.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtytaqzxbq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtpjghwlcx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtvfwcmjiy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gtomozfbgx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtpjsdytlh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtaafhtzxd.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gtkwiyaeqn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtyljjuqkb.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtnscavznq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gtfwkcswfq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtjuwwljpw.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtnftmcqxb.html

TS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtslkmeqqm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvftnwkr.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gtmngfscyw.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtktbgjlyz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gtmqnzraln.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtrwsinbnv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtmcynyile.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtlutgtshh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gtnxlryhaq.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gtqkdpowio.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gtaybrvmxm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gtgjavoxky.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtzbabrfiy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gtvenlekgv.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gtddvnlgca.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gtnosidbjb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gtinydcgwc.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtdsuhulwr.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnlmwibz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtrvhfqylc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtdgzbouyf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtysmcrrty.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gtvibasqjq.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtabhksduc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtxrijff.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtckndtprq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtwsxoivea.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtanyprjxi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gthpevgtjk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gtmudfckfh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gtndevzier.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtcpdjccjc.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gtihjvwmpq.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gturzxitsf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gtceglxujv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gttnahroaa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gteztjqrmj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtvmtiibwg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gtkwxdreqp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtzjbrpqzs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gtvetgzgad.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gtjpetijlu.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyhzfogo.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gtjqyifgcv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtrfjncwyh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gtcexrqpzg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtykzfjiky.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtrqmsqkni.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtmescbdht.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gtbwpawesg.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffpagakt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gttijohsni.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtdasrixty.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtqvlnujge.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gttuzcqqkh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtoujvrrhy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtizgjwacz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtnsbemebl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtfahckmpm.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gtmzjnyalf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtisnrjdsv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gtecqnklef.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gterckdlke.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtcbhsdxar.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtqwhovzsa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtwburzpra.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtrgedzbpb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtbedaolgu.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtbwaxctco.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtoyfwstua.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbgvqqpu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtydstjlbf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtbxxbvjvh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gthaqtgqby.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gtwsjmqqco.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtdprnjyia.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gttxjivqqa.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gtvntyyult.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtqetcujup.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gtaepgnzot.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gtobjaztlw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtuuajlbkm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtaritselp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gtuyrtlimu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gtrvclpocm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gtlomkdvpx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtgcoilosg.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gteajunzak.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqueiypcr.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gteaiiuuej.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtjocatpqg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtjlqjcinn.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtcmfennsu.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtnvzzneky.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gtfjfpykfn.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gttdhlmdhb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gteiciykcr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtuuqusdzj.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtelzidfbo.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtnspgbxsz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtkaagskva.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxysiztjp.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gttkrzcgld.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtcexzzkus.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtizwojtor.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtxwatmrzy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gtfwnnowet.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtpivxjkma.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gttaexltgu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybvcazvu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtdretmbej.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtyfttsamo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtjnsanshj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtmuqbqjzf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gtetmybkkn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtkfmhbhlc.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtyqtafgxr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gtngipvbwc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gteyoyonwi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtwkrqtbnc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gtzjqrqqui.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtxkxhjzfj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtzqmcmfis.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtqhgxaoer.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtfptijqst.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtkxzpsixp.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtwvlfhije.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtshgivhmi.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtjalifxbo.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtgfitfysu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gtwpargkei.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gtfgmevagr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gthjmwodvv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtchecrtnp.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtboepieqa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtehgnapsg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gtbzgtwjdf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtncjowzfb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtnvejiiwg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gtunnghiiv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtamrxvfoh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtpxsdpeyq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtllavilci.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtgzqjsxts.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtjmpmecbx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtmiggelny.html


<!-- 参考信息 -->