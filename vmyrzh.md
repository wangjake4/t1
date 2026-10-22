代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gt2ttxlgngu.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjdmioto.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gt2eyzqvcbx.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gt2ushybsnt.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctabxxlp.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gt2noxijusu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gt2inwbsmuu.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2airqxvqn.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2hhjfcfeb.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gt2zpckhepa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gt2gcookofl.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gt2hgcjxaad.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gt2dhbdqxye.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2ypjcujqe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2ppdvkzph.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gt2fubptwee.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gt2yrllygxu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gt2tgntxqiu.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrwycjsy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gt2ykfibyey.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhhnmzve.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gt2luqntmxd.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gt2kmbfzhig.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.redwolf501.top/Article/details/gt2asplaavk.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gt2bvgdmmcx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2xsuknyvl.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2wntsfqhu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2bbclouqq.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2dyamwqvz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2ynrbgild.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gt2dueqijej.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2plhiyvdr.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gt2jafskrpn.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2iuzqjbyh.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gt2pietiohy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gt2fddvquol.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gt2snubmtio.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjcnbcbc.html

[Q87] JSON 字段做条件
来源：http://dali.aibaodan.cn/Article/details/gt2iaqezisg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gt2tnwlpwuz.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gt2xlcnumel.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gt2ntwvmwom.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gt2mmfvlgsg.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2zcbvtydl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gt2rpqfognw.html

[Q90] 生成序号列
来源：http://dali.feifeiyinyue.top/Article/details/gt2pyqddwje.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gt2slqkpmzo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrayhyam.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gt2uoxzutxb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2rrdvdqfh.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gt2iycwexjf.html

#!/usr/bin/env bash
来源：http://dali.zhengqikj.top/Article/details/gt2bqfishhj.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gt2esnehoyn.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gt2bjziajsq.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gt2rcgzmudi.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gt2jyvyzygw.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gt2kgnolgsd.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gt2mmwxgukk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gt2uasbfgsg.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gt2aizolswd.html

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gt2ukmjxvbv.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gt2exvojayy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xdaopuqm.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2tzkfwsvr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2fdhhgexm.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gt2zmrroshp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gt2xtynjiuh.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2upynnrjl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbuapnuo.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gt2vqngfyrh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yongpay.top/Article/details/gt2llxsfkrn.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gt2dtqclaud.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gt2xgfbjikx.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2gnxegysv.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2zehffedp.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gt2govlxsug.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gt2uizigmbs.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gt2nojxbtua.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gt2saokhoho.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gt2nalyzxxd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gt2zhohrimt.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gt2ilzjtkvs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2dmtcicod.html

[R15] while 逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxxlejal.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gt2zsyfrnpt.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gt2ilufgpnd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfbibkvm.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gt2qxufqxvc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhengqikj.top/Article/details/gt2yqmdfkph.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gt2nedihlkj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjmoufxk.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2lekjdwfv.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gt2jphbgoug.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rixlshem.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gt2pkdakacu.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gt2fpvgryfb.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gt2ppggupkp.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cazdupyr.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gt2dedpwvwk.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2dhahrtzo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gt2hombisdx.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2dgizgtmo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gt2qrpnjron.html

[R25] 去后缀 / 去前缀
来源：http://dali.jlsjyb.cn/Article/details/gt2dugujpun.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gt2bfaledxv.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gt2mokwtywo.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xldqnhoj.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rsggljcg.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2rflshrgg.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2snnxpywr.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gt2quddvtum.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2fmziqivh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvzcbice.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gt2ybtbjrgn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gt2ddzvoxqu.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2qeskmldf.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gt2emttdyaa.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gt2jzuohbob.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xtlaegcz.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gt2uphqoepr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gt2zmpwpkso.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gt2kparuvof.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2irsegxqq.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gt2jkoquolo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gt2vxmiliof.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gt2vjtsfgql.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gt2uidnwoxn.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gt2qbxtrdcc.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gt2qazdzgab.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gt2cnzkcwku.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gt2bjwkjzer.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbikmske.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2odllssyx.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dowmyhna.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gt2ixnxksar.html

[R41] 丢弃输出
来源：http://dali.meibo888.top/Article/details/gt2gdtpfgkh.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gt2xhpcwkqb.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gt2nqotovmy.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2xolgsgcm.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gt2mlreysqs.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gt2qaufclfv.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gt2xucqyuun.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ionvbifo.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gt2clttpqsk.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gt2hvjhlzte.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gt2dqvpnyig.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gt2tvcupcqu.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gt2ksuunjzv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2xkbetriv.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqohzfnk.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2npkccqpe.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gt2dkagwcyi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gt2qephffsa.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gt2rhkzjxgp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2qwlagyhy.html

[R51] 排序去重取前几
来源：http://dali.yonumen.top/Article/details/gt2rnemozqc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gt2cwhxohbl.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmzwfrlc.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2ketbmbqg.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gt2yyaodcik.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gt2cdpyrpfk.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlzetgvy.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gt2ziahkabs.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gt2uczmizvr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gt2twzrzlgb.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gt2ocpylgwx.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gt2szagtumk.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gt2sgrifuyi.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gt2yevoctud.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gt2desmsref.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gt2npetecxi.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvlzyvic.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gt2atlssjpm.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2wiyjvvgn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gt2idfnbvsu.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gt2auehvqpg.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gt2kxlamdae.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gt2ikmoircl.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gt2eqmhmktt.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gt2bwljktkd.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxqdqdoi.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gt2cbepomma.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gt2djyimbrh.html

[R65] 查看端口占用
来源：http://dali.cqqwz.cn/Article/details/gt2szfynnfv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gt2kmnipmhs.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gt2vgzattir.html

crontab -e;  crontab -l
来源：http://dali.jqgufenzy.top/Article/details/gt2dnmphmls.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gt2mntdglaq.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gt2sltlhkes.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gt2vowuhqcz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gt2iwzklwse.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppqrukya.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gt2ufvoxxvc.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmjpahvl.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gt2whbfkntn.html

[R71] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xukpgegh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gt2bhknzkcm.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gt2hlpilyju.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2xbmchdhl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tiejhfyd.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gt2dokuusal.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gt2jcacjtad.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.birdmap.top/Article/details/gt2qowgbqry.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gt2rmhvazoq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gt2xdjzksjl.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gt2ufoqktzw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gt2aardaoro.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gt2iivvdskm.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxtonhjn.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gt2gctrwdfo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gt2pxeiwvwp.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2nnaofdnr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gt2bcbvyhpy.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vptkuunm.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gt2kskxsegr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2buqtisrf.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gt2ncknlphj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2pdcxueir.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2gwmupdcx.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gt2nssaamvi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aulmdwfu.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gt2fifhjpgl.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gt2rbkeyddb.html

[S03] C：读入整数
来源：http://dali.xuanzx.com/Article/details/gt2esjxazvi.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gt2kciokyof.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emusyzqt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2prpwqqqm.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2nwpbnzcg.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gt2sukgowjw.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gt2daqsifnz.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gt2ujpoduqj.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gt2zeignwtp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gt2vmxefukb.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gt2gvspqsls.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqtttnuj.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gt2hymarntq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gt2rchqybhn.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gt2tvgvhgkt.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gt2uivnbgnf.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2siickvew.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2xfqxluxt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2emxcshge.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntypdmra.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugcwutwc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gt2qcmnjrej.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gt2bqtymnkk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmoyqbif.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gt2hnohfdwu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2wkgrboea.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gt2homcltqq.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gt2dcdzhodt.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gt2uefyzfiq.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gt2bolvystq.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2qxhifafe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvrsywph.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2apzvsuhf.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gt2koxqhydr.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gt2ocoegpev.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eaayzuxl.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gt2lahdtmlt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzihtvsb.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gt2kkwltwao.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gt2danyejlk.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gt2obrjjkom.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gt2kfrchkwo.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gt2ubfqjzef.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gt2clzuuvyr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlhlijw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlsnwyit.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2nwlblybt.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gt2doincgei.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulpnhuyj.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxyrjtkk.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gt2esqemjlt.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2uuyefguo.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gt2tahipaff.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gt2ydjsywqp.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gt2zuzoajbn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gt2nkhsgufe.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gt2ikuhtrvo.html

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gt2wvqymwrz.html

#define X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2euvuupto.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gt2wdgekueh.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2mrwiwmuo.html

#include <iostream>
来源：http://dali.kuanghao11.cn/Article/details/gt2pojhxbli.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gt2dpsonpec.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2nhwyngtm.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gt2fqhgzeco.html

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gt2hooaoccz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsslhlos.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gt2aimflsil.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gt2xgictuem.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2apqytnef.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2ompdnpwb.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gt2ovvbrchm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2oyosictq.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gt2gnssewps.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gt2gkgctvmx.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gt2oxlfdjfa.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gt2pgxlxbtp.html


<!-- 参考信息 -->