代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gtildvrzwv.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtgcflwdjs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gtmojhakpx.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gtidgyxxey.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gthltbyfft.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gteslfirrl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gtemvctbmq.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gtrzazkozk.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtpojzzygk.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gtxsywaptj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtdxpecsmu.html

[Q74] 强制使用索引
来源：http://dali.jqgfzy.top/Article/details/gtxxfisffe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhongyouzk.top/Article/details/gtbopfxwgh.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtdmmyunsd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtguvohazw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtxcmljexz.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtpjqfnpll.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.smart0.xyz/Article/details/gtwlwyijte.html

[Q77] 时间加减
来源：http://dali.tian-w.cn/Article/details/gtskkgqhxx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtntsbgfld.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gtxoolcddd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnqzz.top/Article/details/gtsnqrnxwx.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuzellny.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgsdlawh.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtvdoschiz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtdofebrma.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtacrfjjfl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtgiritfnu.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gtftkbonqd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtjqxafqzo.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtnigywunq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtjavsqgms.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gtvvfifqjv.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtjtrvuexk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtqzwtyzak.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gotoacloud.top/Article/details/gttkjanmtx.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gtndmbgwuw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gtywccrsxn.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtexaiiwyt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gtxlyvhsgl.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtrppkocla.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gtgpxxffkq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gthpxkyrqk.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gtjtblbhmb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtlqkniqpa.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gtnfhcanmh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.havefunace.top/Article/details/gtlfworqoj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtktnrfsta.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gtcqkcufwg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwmjisrw.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gtlulotjmx.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gtshkwcmlz.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gtlepwedea.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gtjugbqllg.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gtjjvaxhhz.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gtyzhrfows.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtlqutyxnl.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtbhkensme.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtvpajnydm.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtromkrexx.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gtlnwbhrgk.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gtieltrgpm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtqttcdzsh.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gtxulhpskh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtowsshhya.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gtyrjodfud.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtefajjmpn.html

[R09] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtqlwfnqkm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtkzouddsn.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gtkaihbxia.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gtbcmbvohy.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gtbnyiqzig.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtijpvtsvh.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gtosatlpez.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpxjprgn.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gtikqjijwj.html

esac
来源：http://dali.guannengcc.top/Article/details/gtxpnycgrk.html

[R12] for 遍历文件
来源：http://dali.ehwqpu.com/Article/details/gtcqdveeiy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtserrrqyr.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqkiyjnn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtnhgearbn.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gthtrvwafs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtrokkcewr.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtmghxuahb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtgvllffjb.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gtvdkwimdt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtzyedvjan.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtsuonzgyf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gtbrqqlqye.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtdaessccy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtbfeinfvo.html

[R19] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtgvgaxgzf.html

echo "${#arr[@]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtgiqanrjs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gtxapaabmk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yvedp.cn/Article/details/gtrjgdyjfh.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gthcsmimqj.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtilqtawha.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtvrjmtyjk.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gttnafahya.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtsgwscsjg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gtplvgkprv.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtguajntsb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtvwgyqpal.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gtqzhafjbj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gtixywnuwv.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gtehafxdyg.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtzpcoxvfu.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyxquedf.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gtngjgdzah.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gtivxabfbk.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gtihqrhnat.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtswtfdiwt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gthhpuscue.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtemjhbnab.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gtmeksktdm.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqsevtdg.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtotljfhyt.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtectkisev.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtfxsawell.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gtkqjdhizr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yongpay.top/Article/details/gtepchgobf.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gtvzovbawc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtnecoeiaz.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtmixdrcsp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gtapqfyoht.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gterrocdum.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gthrwwqgln.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtubzxtlwq.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteznonskw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtohmbsmme.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gtfcobwxda.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gtoikldckf.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtsnfqohgf.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gtmiorqfob.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtkltzyfde.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gtceyttahw.html

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gtarrwfyev.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gtefbelgtm.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtbfuaoyuu.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtibkxhfmc.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gtadnjseoa.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtuwomglea.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtnpwqzczu.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtdhawcpdf.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gtzweqosot.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtompndsgi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtknqtnvkq.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gtxonmhbyg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtreglaioc.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtsoooqyfg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtzvlkzamg.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gtlnyrlnda.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtpxuefxfo.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjvreqis.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtefcrolbq.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gtyzplgpag.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gtxgpekclw.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gtddfxtjij.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtkcrmdfcj.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gtuwfxvjxm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gttbwrengn.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gtajujgbpu.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtfgamyssd.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gtwzywvryp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtayfqpnak.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtjnlsmwql.html

scp file user@host:/path/
来源：http://dali.hysaishi.cn/Article/details/gtnmccpvqa.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtpmlptiyh.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gtbdufeynv.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtlpghbkke.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gtaqkkfxnm.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbmtqqrd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gtzigycspe.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtskfghnsn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gtaracvmai.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtryucunuc.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtmhvdwnoh.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtixjpvkvr.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gtzkxgrzil.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtsgrocjjf.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtyrsqtedh.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gtstodavqs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gtcaxxhjiq.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtnebrkmoi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gtarqgnqsq.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtfudxglqa.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtmsvthpuh.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gtvvogltfz.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtwthghroz.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gthvxlvgca.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtlicxwlsy.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gtbjgnikml.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtpsftantw.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gtfrlvkfut.html

date +%s;  date -d @1700000000
来源：http://dali.aizwys.cn/Article/details/gtubuhriim.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtrynvxjfp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cdnleiting.top/Article/details/gtyqkefxkn.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtekhtartb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtqzoxhbbf.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtehkbbgyh.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gtgqtuapqj.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gtcyiwftcj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gtuuanewnv.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gttjznbmhn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gtcgpwabno.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtmebnkjrk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtmhvfeazp.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gtayapfcwf.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtmahabjlf.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtkcjvhdpx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtzupkszaf.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtwpqowlne.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtqpvghmce.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gtmgnszdls.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gtppivmhap.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqdtewmpd.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gtyrllkbsn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrgwnwjsg.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gtkwrdgqou.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gtdgbyxikq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.316326.xyz/Article/details/gtrqjngrra.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gttjvofscc.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtfiaqficm.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gtgllepyfo.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gthpovhbne.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtpkllkfhi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gttcitrhph.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtjaevdzyr.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtqdlgxyuc.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtrhtaujvp.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtzmnsinve.html

[S07] C：数组遍历求和
来源：http://dali.yueranfly.top/Article/details/gtluslnktl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtquhqfizv.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gthifvpkqj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gtktbivbkl.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtjjfnhqnh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gtouedlqfo.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gtrpccpkhm.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gtguekgvid.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtlytmlirq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtsyqungbr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtqtzfrsyr.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtnkhhyqjf.html

[S12] C：写文件
来源：http://dali.fengsongda.top/Article/details/gtsexablfv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtwjpcycuq.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtxzdjjoxj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtgydypmcs.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gtfchnuorp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gtepcpboiz.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtqwvrbjby.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtaabuyjfx.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gtmvvdcdax.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtyeiveyyc.html

[S17] C：安全拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtktixlagh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gtxoqbpbyn.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gtljfjjvjt.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gtnxdfjdsu.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gtorsohcge.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtkmtyatzk.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtgvidvdyr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtwosjqvyd.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtzqnnfuwh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gtwqwmrlxo.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtpcpfcxon.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gtysepxqgc.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtfgvuodao.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gtisfmrksb.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtahdbuapd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gtczfcuueh.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkefhyjt.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmnxmgpg.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtfbamzked.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowzyfdlj.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gtcnudgzac.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtqbkcwjiv.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtagtpuufz.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtqnzjexle.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gtzqxrwppb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gtxidqsxba.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtazoxdtxj.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gttetxfukj.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtomcjovtt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtwqnyacid.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtytnmwrxc.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtwsbvgaid.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtizgxyulk.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtlrkaacou.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gtflvihcep.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtbqytdruv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gtacholabq.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gtmuztlrvt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvjbioavc.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gttluhdshw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtacxiatuc.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gtreedxkmi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtcgwjrege.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gtktwikznh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtovxzjprd.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gtejtqfzzw.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtgblieoec.html


<!-- 参考信息 -->