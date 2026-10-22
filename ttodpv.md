代发 wailian999

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2khhmghro.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gt2sjjrvgzt.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gt2vzsedwsw.html

COMMIT;
来源：http://dali.shzxlz.cn/Article/details/gt2xlgpwtso.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gt2yfhmxmmq.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gt2wcubycrs.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gt2bvckiklt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gt2bzcjbukp.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gt2mvfihxoa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gt2tolxhkbq.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gt2ajypkgqi.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvkmsrce.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gt2qxeaogzw.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gt2hmymbzbf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gt2laswiwuk.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gt2nlvdrxjc.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gt2xkdbddmb.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gt2ldhetdhw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gt2rjteuvzd.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gt2bcpnyjaw.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijlxsffp.html

[Q73] 查看表状态
来源：http://dali.nanxuanxn.top/Article/details/gt2pzbaukrd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gt2ohfrbcsx.html

[Q74] 强制使用索引
来源：http://dali.tianlin.xyz/Article/details/gt2xympldiv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzsdgmvn.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2pfrohull.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2mkheuvkq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gt2hngxkqpb.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gt2vvkebxyp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gt2gtgfgbhn.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gt2uepjgchy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gt2vmgxnvlf.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gt2gzycwipq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlvwuunu.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gt2flzfnfhy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gt2laluzqgp.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gt2bsxspbjq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajgrysrp.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgilhjfg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngsktggy.html

[Q82] 字符长度与字节长度
来源：http://dali.zycfv.cn/Article/details/gt2evficqnu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2swilpeks.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2uzzkecul.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2ozfnniqh.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gt2rtjnenfv.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2qsqefbaa.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gt2gydryryw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gt2qadaiqjt.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gt2dgnpxnat.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangshuangyany.cn/Article/details/gt2llagxzaw.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gt2pdiukxqt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtoteoyk.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gt2xpsmvdyw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ieguejtf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwzumrwn.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2ggrafpjj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2crsdemjb.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gt2cqznklbw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gt2lstyycwh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2tewhseau.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2hcowtvgu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qxfyxhnk.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2fnkkxmbz.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gt2givbbzti.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnrkyjbz.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gt2bwnjllxe.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pevgfabx.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gt2ffdoojfq.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gt2leryuxuk.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gt2nwixnwyg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gt2aznpvdzx.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2ytueslbm.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gt2nukjqknu.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gt2arzgxsqe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gt2uqcbxiyc.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gt2zqvvgpwz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2zdjlbxph.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gt2eftkqqbk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gt2mtymbesf.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gt2vcelllkx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhtzomfr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnjaawv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlofaurh.html

[R11] case 多分支
来源：http://dali.ppjwa.cn/Article/details/gt2zaaxxyod.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gt2ooovahxi.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gt2jmwnvjcr.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gt2vpgspzyq.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2ahnogldb.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gt2bvbzfgxj.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gt2adhmmbzu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gt2cecqrvvf.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnebzkpb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2gjleiesg.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gt2yuhoxgtl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2fkxqadqz.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2qpishemu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gt2gdsejnij.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gt2gnfjuurw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2ruvlllwx.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gt2aelwglpz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gt2vdwyuusn.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gt2cbbwnigl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gt2jczpswiz.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gt2yurnlbfc.html

echo "${#arr[@]}"
来源：http://dali.cdnleiting.top/Article/details/gt2hdoyhnbp.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gt2geutmlmu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.snrcjt.cn/Article/details/gt2petafzfz.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gt2gdouldmk.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gt2nwqrytxz.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gt2ywlereui.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gt2cvjtukqd.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgitzedb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2xtbbaqrw.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2rgnghysh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2nuqvwpgc.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gt2sspjntgk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gt2uwsyicba.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gt2igywawmo.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gt2inawznin.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gt2nygxpxuh.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gt2cnmuaxow.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gt2zewfcxrv.html

echo "scale=2; 10/3" | bc
来源：http://dali.vqdsnc.cn/Article/details/gt2bqjsjtbs.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gt2maorkvxi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gt2xpzjqigp.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gt2mbbnoveo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gt2ftzgimtv.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2haydzcfg.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gt2ajbbhgus.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gt2fadvsgsh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gt2pkrltwew.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gt2nsloicvf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gt2qanlxddk.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gt2ewdrxyhh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gt2yuspzqtr.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gt2jnvypbpq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gt2ypjocvqd.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gt2ukuubdnd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gt2uuxpbgdy.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gt2tqqxfuhl.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gt2zhrscctv.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gt2azqbbgsx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gt2ibyzjmrh.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gt2nsxjopsd.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2kasikkko.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gt2qclrvwlb.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gt2dxysxxom.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gt2zjhiibpo.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gt2ijcemgvl.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gt2pqiiuenx.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjzrbxpi.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gt2ukehwiuq.html

find . -name "*.log" -type f
来源：http://dali.svipenyu.cn/Article/details/gt2tsrgkjkl.html

[R44] 按修改时间查找
来源：http://dali.yueranfly.top/Article/details/gt2rrziiasi.html

find . -mtime -7 -type f
来源：http://dali.hnqzz.top/Article/details/gt2jqyxyhke.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gt2csytrqjl.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gt2mcznfguw.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gt2irivardp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gt2ogauhaqu.html

[R47] sed 单行替换
来源：http://dali.chenlongwang.top/Article/details/gt2nzgtfnrm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2dnrnxrbi.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2haohgyyi.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2ywtjkdsv.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gt2fzjqmkrw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gt2zgtqbwzt.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zewfaxvf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqzsulug.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gt2zryyqnog.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gt2ipebvgpi.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gt2lfmrxklg.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2sbzgqefo.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gt2zqwltulf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gt2aaxsdebf.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gt2toifdvmj.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gt2wrfhhhtv.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gt2gzmtfqfv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gt2xiaenbzz.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2jzconvzs.html

scp file user@host:/path/
来源：http://dali.cdnleiting.top/Article/details/gt2ispovecm.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gt2ggcesflf.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gt2vubtyyfl.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gt2jpktqjpz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gt2aljjkdsj.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2mpffpctr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gt2dxscbffb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obidkfyg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gt2xakxjkja.html

[R61] 磁盘占用
来源：http://dali.aibaodan.cn/Article/details/gt2kyffxfqu.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gt2nugzdrpc.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gt2qstjwtxd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnjfrba.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gt2sjhxssjr.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wshakjla.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gt2emgkrxxl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gt2utlpuawj.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gt2eqzbglvh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gt2zlemowdf.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gt2siewfeop.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gt2rjphuorn.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gt2ruxiuqds.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edjlzkpr.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gt2namowlfq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gt2vkbgbbcl.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gt2hwiydahn.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gt2ioxqmjvr.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gt2dghpmwgh.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gt2qjapcvbz.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2wcdgphup.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gt2fffkzuwp.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gt2yyytrvsj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gt2foyrhpbd.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sekjiosc.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gt2fizwonvg.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gt2samhcsja.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvrjmbcp.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2mumheqmc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gt2jxndvjpp.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gt2uzqsoook.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2lqymqiku.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gt2zqpxyfvy.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gt2pxjjnggs.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gt2zdayxwjl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gt2bosuraaj.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2pdtypjqd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gt2vhxirapx.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gt2hurmaqsv.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gt2qssmfluu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2keowwdtw.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gt2xeqlvbdb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2leqschpe.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gezoumly.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gt2wawxsfyk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gt2hcjulych.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2xflsmdsf.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxsegaus.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gt2xuuzhjff.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gt2aqyeixdo.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spvutagd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2jobvemqc.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2uqawqvmg.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gt2morckecs.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2whoprevw.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gt2vsetwrql.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwrraeok.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gt2qsvgkqde.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gt2avppssjf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gt2lxpxolaf.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gt2cekxucza.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gt2pnllnzvi.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gt2wynzxcgu.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gt2ofwichif.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjkoaugr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gt2ubcfhcul.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenzaomai.com/Article/details/gt2irzgcuwl.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2rrpkkdry.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxamtulf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2dwtwyfli.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gt2sxcnvkhs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gt2bscsjqet.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gt2zqwadehb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gt2dmqgezph.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gt2djykqrtd.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gt2tpfgysax.html

[S16] C：位操作置位
来源：http://dali.jqgufenzy.top/Article/details/gt2giurjwdz.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gt2apzormjy.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2yayrbkez.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gt2ltisesle.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gt2wpdlyayq.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gt2lcicwlvd.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gt2zhkgxcfb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2abwljlfr.html

[S20] C：二分查找
来源：http://dali.snrcjt.cn/Article/details/gt2hlkpajzk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdvwqyis.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gt2xhecsnht.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gt2nqapuldd.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gt2qvbrukca.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gt2doumlihs.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gt2dvhjkhmt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gt2zgloeseh.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gt2jqkdhhdr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gt2fbxdvbjq.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2oikxeilf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccblphbn.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gt2fvqedrbq.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gt2eygwnxxe.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gt2ngfasxtj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkhgkbx.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gt2rsyjcgsk.html

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gt2rkfiibzi.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gt2jcthwroe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gt2tjxbspty.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebyfsibv.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gt2tracgwll.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gt2sdfelzca.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gt2utweygvk.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2llbxmwnx.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gt2meoiqurt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gt2vonsuqbx.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gt2qpvzdpei.html

std::string s = "hi";  s += "!";
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqvenhwo.html


<!-- 参考信息 -->