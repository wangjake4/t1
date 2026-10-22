代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gt2ntqcdcwv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gt2agtxtywl.html

[Q68] 保存点
来源：http://dali.pengpengdd.cyou/Article/details/gt2kljptehh.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gt2kiwmjgnj.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gt2htcuzgkn.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gt2xpeljmbr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcpxvhaj.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gt2rxjmvbfo.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yuauvmov.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uspjowsd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gt2lzaptlfv.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gt2wqdennjc.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gt2uknivgkl.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gt2jkvcomxg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2fcmchsox.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gt2mevztldg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgsnwzil.html

[Q75] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2hpadkchv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2abxyuqrd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gt2fejkfxvl.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gt2yduzqleo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gt2vbrxzwhq.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gt2getzkywp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gt2zhtyaawg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bktwkeko.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gt2byjkzrnu.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2uwjtbsxr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gt2fttbtmnb.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gt2qxupmqan.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2terqlqpw.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gt2nighpkfz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2qdksmmym.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvgntefu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2puvholgn.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gt2pboliapr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2mtebzhey.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gt2xwytizxb.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2lbpurbol.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gt2cojnzvrb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gt2lqmwnera.html

[Q86] 读取 JSON 字段
来源：http://dali.dashuyun.cn/Article/details/gt2nhegujlq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxcnuqqf.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gt2krdiwhkq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gt2hjzkfful.html

[Q88] 行转列（条件聚合）
来源：http://dali.xinyue.icu/Article/details/gt2zeiuepyq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxuzcdhb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmeounae.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gt2eunzibbz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oazgwrmu.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gt2qjhangja.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gt2bjgnwfkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2razzrqka.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gt2iqsnvmco.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2fidbjhel.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gt2uotsjskg.html

#!/usr/bin/env bash
来源：http://dali.cdnleiting.top/Article/details/gt2tfbghlvk.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gt2zfthjonb.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gt2xsvzeuzs.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gt2tonodksz.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gt2sycxneua.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gt2xxvxrruc.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gt2ogidvzwn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gt2ljmhkdvq.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gt2sfgrmgao.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gt2isuastse.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gt2xcpbapep.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2zkgzabhh.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfcvyyaw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2spxjnuqd.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcxzivaz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwjykgm.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gt2jkqptlqf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2jjshlrke.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gt2dxkcpaun.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2umohrpdz.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gt2auitlmxh.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gt2uszbpjve.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2ecirurnp.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2wltbhtwl.html

*)     echo "未知命令" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwgdogvh.html

esac
来源：http://dali.cdnleiting.top/Article/details/gt2obvzrtcl.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gt2lhjzefdy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gt2mrhrazwt.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gt2lwvpbdmt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2udgstaml.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gt2cgtrzbqv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gt2nbojacyl.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2ceefzyni.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gt2jqzffbgq.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivjxfygh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gt2cnyvxyxi.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gt2fknrhgfj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gt2wamqijba.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gt2jjsgfadc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tetzgahg.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gt2tmtrwaoi.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gt2wtskrjpr.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gt2shbtlspv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gt2vzjuygpx.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2saeqande.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gt2ztmexzbv.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gt2jbwaaknr.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gt2akpzdwew.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gt2nnsbqtdi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gt2juqwffmn.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gt2kwvscqyx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2utffmxac.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gt2obasxqbk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gt2djlmwmvl.html

[R26] 命令替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2aohbsyed.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gt2suogdizp.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gt2iftzznzc.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gt2zgchrjcn.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gt2kmnhkygm.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gt2xsuxbvks.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gt2nabdpwje.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgufenzy.top/Article/details/gt2mjywsrjj.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gt2ynvmlwyu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gt2xuzufxgw.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2yxxahfmz.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gt2qnhyjvvn.html

[R32] 参数个数校验
来源：http://dali.yonumen.top/Article/details/gt2cjbhajxy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gt2tvclsymd.html

[R33] 捕获错误并提示行号
来源：http://dali.zdqjudy.top/Article/details/gt2zmtghvms.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gt2offfidta.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gt2rdisknua.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycgwmhxk.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gt2xnfgsxxf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gt2qnuawegi.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gt2rzhcgben.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gt2ymqggvfc.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqnehkjt.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gt2lgzsqdbf.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gt2iasfvvvh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gt2buwtrlcl.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gt2gzmzktjp.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gt2ifrqzuyx.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iuurihqw.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gt2gypmpfaz.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gt2fqhhmdpb.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2gbeelgwk.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxmnkfop.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gt2xsihhupi.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gt2rfgrwuqb.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gt2wbzgzezi.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gt2ckzehwlh.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gt2dtagkbfb.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gt2ooeuljns.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gt2vxrvjpqk.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gt2mafflode.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gt2mtrgqazv.html

[R47] sed 单行替换
来源：http://dali.hywenlv.cn/Article/details/gt2fccugdit.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2fletzxni.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gt2tnuaatho.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyceqbkn.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gt2zztcfhmu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gt2uqniuyga.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssmgqlaz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2tqhylolw.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gt2xzggroqs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gt2ythgrtlj.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gt2iiitsujr.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2xkxoneuu.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gt2mmvjuccf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gt2jufnedcp.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gt2zqswddjp.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gt2awesnmfd.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gt2zeguctaw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gt2oimtgbjp.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akxqtxxm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfwfjih.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gt2fipxaqaa.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gt2tqblrcwq.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gt2ufswmpds.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gt2uapzyjda.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2uiosdlzu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gt2euiacmqp.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2wjrufhpf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gt2ajisrybh.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gt2fkxqvafo.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gt2zmgobfqk.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uybfbjre.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gt2sgwoteet.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gt2cktlxguj.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gt2ogectvhz.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gt2cxwyaoko.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gt2txucekoo.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gt2zziyjpal.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gt2xklhltpi.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gt2zkccwpmi.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gt2ypjuxdrv.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gt2thknfalm.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gt2aikfiazm.html

[R68] 计算文件校验值
来源：http://dali.smart0.xyz/Article/details/gt2stewngbe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2ylfpaeni.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gt2xbtgudgo.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gt2tnsqaiso.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gt2kjwboycd.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gt2zeqivtya.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gt2byhnfqvt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gt2mrxxpybb.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gt2onjolone.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2ubwdojij.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gt2yfzfqwto.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gt2onpebjhg.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gt2urmxvisr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gt2eenafidx.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2odihrnti.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gt2aixepfgz.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gt2zbdhaslz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gt2ewydcesf.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gt2eiifplsn.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btcelsvo.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gt2kemfbmkc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gt2htawmcni.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gt2kzdeydib.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gt2gsnhwpef.html

[R80] 查看脚本执行耗时
来源：http://dali.redwolf501.top/Article/details/gt2yywzaauf.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gt2mkrtusxp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2kgbljfxo.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gt2qmyeyzwf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2luvdpvqk.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2pcmaarsi.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gt2yziuroqh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjzesnla.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gt2cnioljsq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gt2znjhpzgm.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcrencxv.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gt2fguonmsb.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqxbtnyo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gt2hdoacjoi.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2tdfhubzw.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gt2jcimanhu.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gt2ciyaxfus.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gt2itxgeeud.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gt2uehxdrkl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gt2tjdwyufj.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gt2qjxwprmy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gt2bamfegbc.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gt2cprccqlw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gt2gstanrig.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gt2mmflirfr.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2ewioqjfe.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2mkfiewel.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewmdjawp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2yvntkqwp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2souvagag.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gt2bbomvies.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2furbjcji.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gt2bskcjrit.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gt2liomjimc.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gt2vryynhwk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gt2dyhczsrm.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkqodxeq.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gt2clmywygt.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gt2gqmkkdlp.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqnruxkf.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2zytmwqsx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kblievjw.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2xhzlbkld.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gt2xzzyfauk.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gt2yxvrrjbe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2ttekciou.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwadrjbo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2fswildmn.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2vxhqfcmw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gt2hvfkaucl.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gt2fgmmwbjr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gt2pyhrhorn.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gt2grdelcxm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kekafjau.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gt2pzygigew.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gt2pscaezcg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ybygbloy.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gt2wbqnraqa.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gt2kkyywcym.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhykfvru.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohnptlld.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2lmmxvpai.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nihekypb.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfhjlpbd.html

[S29] C：变参函数
来源：http://dali.yongpay.top/Article/details/gt2aoralxiu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gt2lisxqysx.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gt2jyuxexnl.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gt2pcojgszs.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gt2ocqikyqc.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olckulyq.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2fxkzjfuu.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gt2qfkeleti.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gt2eoanfcet.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gt2ijqcnlrc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gt2fiarsxzl.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gt2tmninark.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayewurzx.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gt2mztlrnfc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gt2lemcyrsp.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gt2cueelmyc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2cocwpqsa.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gt2qwqfqday.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kffunmqw.html


<!-- 参考信息 -->