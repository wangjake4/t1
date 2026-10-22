代发 wailian999

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gt2amalrirn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cqqwz.cn/Article/details/gt2waiyohxa.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gt2vsymojwj.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olqszxhu.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gt2gyoxvkow.html

ROLLBACK;
来源：http://dali.cdnleiting.top/Article/details/gt2yzebomja.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gt2yyvwvjes.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gt2eighkuaj.html

[Q67] 设置隔离级别
来源：http://dali.birdmap.top/Article/details/gt2argllipz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmwdanpb.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gt2jyufqpht.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gt2aedqqcko.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gt2jkahwrxw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yeawmouf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.c1oappe.top/Article/details/gt2sclnspyt.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gt2uxxeeufw.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljifstvq.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gt2bsltalpf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gt2qtkmewna.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gt2qzgjmois.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snybaanh.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gt2xxwjddiw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gt2nczjkroh.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gt2wyvkzohl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gt2dqxxtlem.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2zuvguzga.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2epmlurae.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gt2nnbjwgwn.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gt2pxfyzpue.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gt2xpglwmwv.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gt2udcvatqv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gt2irgbewrd.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2onkkjbzl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gt2jyrjvfmw.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gt2monmxlzw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xggspiqw.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gt2zgukxuzl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2dyxxvbsf.html

[Q81] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gt2ryjhmzug.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gt2hoxamaej.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrkmsbsb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzclwwoa.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2vkvsmdkn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2oszvmbga.html

[Q84] 去除首尾空格
来源：http://dali.mhx1999.top/Article/details/gt2mvqookil.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2yfjonuhb.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gt2cuxqzkkc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gt2crrjohvm.html

[Q86] 读取 JSON 字段
来源：http://dali.yueranfly.top/Article/details/gt2xwtecjoo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gt2gvmwhcgt.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gt2tsrvtavj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gt2xmvgggpn.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gt2aqxacyzo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gt2udowtzeg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tntedynh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzguqgz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gt2steesowq.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gt2gxkqbjsy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gt2akkhxasg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2tezjwowa.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gt2dkggwqig.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxhwzgoi.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gt2qaynxzyy.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gt2eecykqgu.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gt2eiqbxtqz.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtgqxhaj.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gt2zchvpcha.html

[R03] 只读变量
来源：http://dali.birdmap.top/Article/details/gt2bipogwwq.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gt2zptmtoty.html

[R04] 位置参数
来源：http://dali.sweek.top/Article/details/gt2juhmcsog.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gt2olbnalcf.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gt2tbydsryl.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gt2gwzyzryd.html

[R06] 判断命令是否存在
来源：http://dali.sweek.top/Article/details/gt2ibuzncvc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jxwfaizg.html

[R07] if 判断文件
来源：http://dali.meibo888.top/Article/details/gt2fikgnvdz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gt2jmeshyew.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gt2zjcatkdt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2prgunxbl.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2velozzaa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gt2cxexrwfd.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gt2ucbtubck.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gt2zidpvkrd.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gt2wkoofhqw.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gt2hsvdunvd.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2ungpcdiv.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gt2ocvlketk.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gt2unfbptmd.html

esac
来源：http://dali.316326.xyz/Article/details/gt2xfmewiti.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2bvpuxmrm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gt2byionyzb.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gt2macksxfc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gt2ekcwtals.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gt2ruunuefw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2qfcbvlrk.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2qttujanm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gt2yxcrwbqo.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gt2rhowzxly.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gt2qrtilnbh.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gt2ovkhpydz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gt2jssbrvly.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gt2gqdegfkv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2kquzilnd.html

[R19] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gt2yonfsjqm.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gt2opzldjes.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aahefwat.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gt2qhiujgph.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gt2bfoybrht.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gt2lndmdkmd.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gt2eypllorw.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2wymaxdrv.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gt2fmklrauj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gt2hleruukz.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2vekizmue.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gt2yhwmahbs.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gt2qddjbolr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsculcbo.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kuzybynq.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gt2oafsitnu.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijuellda.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gt2erlhsxge.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gt2njfngdjm.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gt2mdtnhwir.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gt2gfxdtykp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gt2qinavsjd.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gt2nlpnftni.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gt2ybefasdp.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2msnlcwld.html

f() { local x=1; echo "$x"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydikdtha.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gt2bgocabwl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2hyklcypu.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gt2zpikrcah.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gt2zikzkhyi.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wctyjqpt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gt2ogsclfsv.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gt2ydlqpcir.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohgwjmpc.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gt2mnhejkwa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gt2rmzjlebs.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gt2vxclfiea.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gt2rbtonlmq.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gt2mcctpcnb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gt2meziptrp.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gt2tghcqjqy.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gt2nostbehi.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvoasrwt.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gt2lddkhpvh.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gt2olxyyslq.html

cmd >/dev/null 2>&1
来源：http://dali.zhengqikj.top/Article/details/gt2lknafzvw.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gt2gxmuboii.html

wc -l < a.txt
来源：http://dali.ivvv.top/Article/details/gt2avbxlchy.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gt2yxxzezyl.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2xobirzav.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gt2qnowewwp.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gt2reymiues.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gt2vakaeans.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gt2comnfwwh.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gt2lnaobibu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gt2aybjahnr.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gt2zpstfuqk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gt2bqwidyuz.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gt2tcxpffpo.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2iqwxxkcs.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gt2odgjjjaz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gt2npvvdufm.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpzadeah.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2fegjodda.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvvkanrj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gt2feezglyn.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gt2npwbnlqi.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gt2padzthej.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gt2udarfmtq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzumqqjn.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtmaxxyr.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gt2wujopgdz.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykzxehuo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gt2kyyusdbt.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2adifygnk.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gt2jalvwgsh.html

[R57] 远程执行命令
来源：http://dali.sxryk.cn/Article/details/gt2eyzqklks.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gt2asemfkik.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gt2pryscwnu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xemsvoje.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2syksznrr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rvcxbohp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2olyumtfo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gt2pbdbfclo.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gt2hvkgnejz.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gt2xyofaxua.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gt2rbvmwlan.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gt2svqogymv.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gt2kvvgwete.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gt2zzapasxa.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2phynxjgd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gt2nctebtgz.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gt2cdwwojes.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gt2kdpraklk.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gt2iwluehzj.html

crontab -e;  crontab -l
来源：http://dali.chenlongwang.top/Article/details/gt2ukrigqgn.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gt2qprgtprv.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gt2gmkwltxt.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gt2rtfkblhj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gt2oswdlcmx.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gt2snuqqnwu.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gt2vvsgpjqk.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxjzhvkf.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gt2wpkrejst.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2xspbsqav.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gt2norfpnku.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gt2vxujmisi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gt2yczyiuto.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gt2wgjrywtv.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gt2aogoplsi.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gt2bsckwfrz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gt2gupnutwe.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2omhkhfoq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gt2vusseloq.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gt2ctecitrj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gt2apzyvtkv.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gt2cdebjnub.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gt2aeyegnrv.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gt2wbphbpel.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gt2wusjaiiz.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gt2qwcbmyrk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybakamnt.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gt2rtmmhgfh.html

time ./run.sh
来源：http://dali.jyoumei.cn/Article/details/gt2woqpjtfx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ostfivvn.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gt2wsqycmhz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2nzmwzmzm.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2cbxouxqe.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2rlnvpvec.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj202588.top/Article/details/gt2auanyybq.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2uugdjkld.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gt2kkprnjym.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbqduujm.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gt2dpwgpekh.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcoqthor.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gt2mfgzbtok.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2nwcufxkv.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gt2cfmhffpe.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2hocryzox.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gt2rkxhzsmb.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gt2wkqzrhnu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gt2jgehbfwc.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gt2jsexosat.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqcbclgk.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gt2aakmrnwu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gt2pnoyipik.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gt2iinoijvp.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vinbcgav.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbsthfnb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gt2kmihhyaw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gt2svaqqygf.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2afktqqnt.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gt2ebkcrbmr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2gbbxrjta.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gt2wfmqrnea.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gt2audzhcxd.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gt2kwespbvt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gt2omrmodlf.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gt2plczpqcm.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gt2stkcmfec.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gt2nowhbfoi.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gt2nuypmsio.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2uregfkge.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gt2ysxnpwph.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2rnsenmtb.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gt2iwcrpgkt.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gt2rdjrsssz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gt2desgltsq.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gt2eklkzjnr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2oypuuqrh.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eravxcju.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gt2qpknzybz.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gt2fhnclhgt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gt2cvdsyspd.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gt2rlnmdmne.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkhbtmuj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfhustx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gt2jtpuonec.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gt2jykxogqh.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gt2rbccatmz.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gt2uxuibtah.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gt2wsmmmzqz.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gt2fhfujvmb.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2lgsdaafv.html

[S28] C：静态变量
来源：http://dali.sysykeji.top/Article/details/gt2tojeyiea.html

static int counter = 0;
来源：http://dali.sysykeji.top/Article/details/gt2pxvatfir.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gt2umqkmgsn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gt2kdeisaze.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gt2hkewdpbx.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukrykbqq.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2gyhjjamk.html

#endif
来源：http://dali.iojbl.cn/Article/details/gt2osbjpmhx.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2lhjbakzk.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gt2teaubnjd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gt2svmmrinf.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gt2umjgxlfb.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gt2tsjlthey.html


<!-- 参考信息 -->