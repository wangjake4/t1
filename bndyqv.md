代发 wailian999

[Q61] 移动平均
来源：http://dali.kuanghao11.cn/Article/details/gt2wludocpe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2lqwdirty.html

[Q62] 分组占比
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwbykeyh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2gaajlzbb.html

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gt2zaidsibi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhengqikj.top/Article/details/gt2azhfzgyr.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2uoktlcyu.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlobchjv.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gt2yapakvzt.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gt2jrzjpecd.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gt2numkahhd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gt2nclyzubw.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gt2eifnipvw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gt2ulrkbhrg.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gt2hhkcdmru.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gt2yhonevrp.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gt2ificakjz.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gt2bpyrcxct.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gt2xwcsrelp.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntzdgnzl.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gt2wjsrsbep.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gt2vkbfnrky.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gt2bjevxnve.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gt2ysjaidev.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2voujsymb.html

[Q73] 查看表状态
来源：http://dali.gzhubu.top/Article/details/gt2sumuhcpy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gt2mtsmoouh.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gt2dzgsopso.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gt2wwkfblsn.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gt2tukxxdhd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2pdfebphe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gt2ryajzgfu.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gt2yzkvzxhl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gt2omlzneju.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gt2sqvrqmnp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gt2eotvetyp.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gt2qhspwaim.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gt2sndrfocc.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gt2pojqkqko.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gt2rztnwgli.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gt2liamejwl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2tcvgnqvf.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gt2yfpvfrkd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2zgmdharx.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gt2xzupuctg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhxkownt.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2rtcsbvmg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2nyyszvey.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2klhdojft.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2nswnephs.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gt2hsyosllc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gt2hprsjtqu.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2fusdurxg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gt2klsankmt.html

[Q87] JSON 字段做条件
来源：http://dali.vqdsnc.cn/Article/details/gt2jqoqzqdz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gt2bhlpmcib.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gt2mfmbcbuy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhjhtvqn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2elpbwwfu.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gt2rzlbpfda.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sysykeji.top/Article/details/gt2hhfxnbtb.html

[Q90] 生成序号列
来源：http://dali.smart0.xyz/Article/details/gt2orwtuzks.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gt2uidqikgl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfnrazqp.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gt2avtwisft.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2qyjmoajx.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gt2ldwlynff.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gt2qniqjtyu.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gt2eothcees.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gt2wxbzxdgd.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gt2hgvbvusb.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gt2jcjfrowz.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gt2oexwvdxr.html

[R04] 位置参数
来源：http://dali.tian-w.cn/Article/details/gt2xskeisgx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gt2dswhepjy.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gt2fesbjajx.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gt2snloitzm.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gt2rdaikmph.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gt2aoqxvzxi.html

[R07] if 判断文件
来源：http://dali.tian-w.cn/Article/details/gt2isdsjxtb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkgxuzcv.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gt2zacivhxo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gt2oyvvwngu.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2mmcsvbqt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2tziopgtt.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gt2vyeshvwk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gt2mnecyfpa.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gt2zchbxmmi.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gt2aayuymbo.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gt2uxmriqju.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gt2ixafaqyr.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2frcwopte.html

esac
来源：http://dali.ppjwa.cn/Article/details/gt2ivapsobt.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gt2tnofbdir.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2lstknxpz.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2gspvxewl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2tmflhlnj.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gt2nedtexjd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrjukueq.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgvzrlgy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2wjrsnrkj.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gt2lpnmgypy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gt2nvnifxbe.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahurantt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gt2cavbumys.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gt2mylyahvz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqohwzmi.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gt2pkdlonaq.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gt2omzbpxgz.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gt2extlqhkt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gt2siqmqwaz.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2irnpmccw.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gt2wswqjoiy.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2hclgsjvm.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uflngwso.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2ruoyadph.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gt2svshbswr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdelsxi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gt2dholvzpm.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgccgsyz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gt2zqrlyjtf.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gt2wzcnigdk.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gt2pjkqeico.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gt2pvmrzhgh.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gt2aamxryvy.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gt2juisuytm.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gt2cmkbmoge.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gt2hcxowecu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gt2eceglnuc.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdunxlpi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yongpay.top/Article/details/gt2fdilwffh.html

[R31] 局部变量
来源：http://dali.zdqjudy.top/Article/details/gt2igaxnuqt.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vutnppnq.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gt2gczqhhwj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmloizfo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gt2jhatbcmf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2lcvjuuak.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gt2ojhubkkw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gt2dsrtvovb.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gt2nypsyoal.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gt2qzdlvsav.html

[R36] 并发执行多个任务
来源：http://dali.birdmap.top/Article/details/gt2iygwgell.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gt2ortckvhn.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gt2kszuexyr.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxmchhdw.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gt2yinzqzzt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfwnoicb.html

[R39] 重定向标准输出与错误
来源：http://dali.yangfankeji.com/Article/details/gt2owvvsjjs.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gt2rgusyfum.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gt2seamwcyx.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gt2ikqoxjog.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gt2onbcmony.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gt2cykkaphl.html

[R42] 输入重定向
来源：http://dali.sweek.top/Article/details/gt2znbgmddu.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2tiuqlfug.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kujcvtqf.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gt2vhtrtyva.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qaspoxew.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gt2msbwhccy.html

[R45] 批量删除
来源：http://dali.kuanghao11.cn/Article/details/gt2mywtrszz.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gt2cdccfabe.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gt2tjhxsmqv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gt2pzjgtiel.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gt2zujdchsa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2dubtqwil.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gt2lgbbvkfo.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2ymhnryjx.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gt2mwabqsmx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuanzhike.top/Article/details/gt2clkvxlxz.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2evdwbmci.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gt2gtgoyltn.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gt2quyfwtnl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gt2pxarnghw.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxdklfgg.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gt2zrwnwrnh.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjzmzryv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gt2mqhmcxuc.html

[R54] 比较两个文件
来源：http://dali.fzhhl.top/Article/details/gt2duxfddwo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyslgsd.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gt2zfwydwft.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gt2itehdufk.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2dqobfuju.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gt2fqrevayp.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gt2zrfjoysi.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gt2prmszlpf.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gt2alfwyrjc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gt2zdomxpmp.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gt2rydtupsj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzjhkfbr.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gt2egrgjidg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gt2hxsivdhk.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gt2qzxhcnit.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gt2lbiftcir.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gt2fjunocbw.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gt2oqdwuvut.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gt2shnvkzac.html

free -h;  ps aux | grep nginx
来源：http://dali.shuidangran.top/Article/details/gt2vqeephqx.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gt2geyaudxg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpynwtxq.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gt2yxawkjit.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gt2mmnxcfci.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gt2bmamwdgs.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gt2vupullpl.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gt2noekiuuw.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gt2bforxyua.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gt2zjlgwlbj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gt2wopomvgr.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gt2zgfhxxfm.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gt2cvodsoie.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gt2alpniadn.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gt2manaqbew.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2cwtotwmd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gt2wurxhyzt.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gt2bbesbzei.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gt2ofxcvwuf.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gt2lknvpnpu.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gt2laopopvg.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gt2gczgkeno.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gt2fuiktkij.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gt2wsdssgsn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gt2armeumfl.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gt2hbiurijs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gt2ujmrdapr.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gt2gwnfewnu.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gt2wamnecjh.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdbtszrc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gt2vlszyayi.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gt2vhcunbud.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gt2utklxydp.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gt2gnycdttw.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gt2njpoxnyn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2zasyphxu.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gt2yfsbcdpi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2jsigykko.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2zgbkyfac.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gt2lffkmtri.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gt2uthxlqei.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gt2uqgxuqnm.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gt2ktcfthoj.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gt2shwuuanu.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gt2taafchfa.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gt2uweiielx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2vmzitaiy.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gt2akznkigo.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2inpyvtig.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2doxyyevz.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gt2cwqmmwqq.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gt2qjzquudc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gt2ltffsjhu.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gt2ohepvprk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gt2ljyljbhk.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gt2wmoyvakz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gt2ogekfeej.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vpwpbwss.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gt2mebszzrd.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2yaglyjoy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gt2jktwdwuc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gt2dwedezpz.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfkkawhh.html

[S12] C：写文件
来源：http://dali.shuidangran.top/Article/details/gt2mhtmzbfy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gt2gtnhlypa.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gt2ngjhputc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gt2nqbcboqy.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gt2hhcflktn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gt2ktsrckqb.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2eojoxlqi.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gt2zniopfmg.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gt2vlplqccy.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gt2bccgzmsa.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2omvbreme.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gt2pmvgrhid.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulcupekx.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gt2nsucghqc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eylxyrvl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2dwlpdktj.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gt2vbtktdxx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2vutmaosg.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpuuipqa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gt2rfqagzui.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gt2celtuvhm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkjrxemj.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gt2gdcozmks.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gt2frptyzrw.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gt2mfymvskc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptndycre.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gt2gmmkicjs.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gezpryrb.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gt2dzpldbdo.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjkzcphe.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkejzzcl.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2drebxyjm.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gt2lqckxxro.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2awpgvwug.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gt2vftehwhc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gt2xyzbnafq.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gt2swaahmyn.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gt2hfdaqijw.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gt2flsihixk.html

#endif
来源：http://dali.pycfn.com/Article/details/gt2kxjmanzo.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2srhkldre.html


<!-- 参考信息 -->