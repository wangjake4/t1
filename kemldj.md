代发 wailian999

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtfbwpjcug.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmcobaql.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtkbrwsisn.html

COMMIT;
来源：http://dali.aibaodan.cn/Article/details/gtxynaogqz.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gttyuidsdt.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gtmwlrgrmr.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtozcechen.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gtposmiokn.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gthrkyfsuv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtzamaqalh.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvekbvtjh.html

SAVEPOINT sp1;
来源：http://dali.tanke756.top/Article/details/gtsyuqfpdg.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrrrcgko.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtqhaapwhe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gthrvspmpw.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtvcaqoudm.html

ANALYZE TABLE users;
来源：http://dali.cdnleiting.top/Article/details/gtqmxvlqfx.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gtuxakyoqy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtqihpdcoa.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gthsumvnwm.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtupnmoexf.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtouxsekno.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtykolbqbw.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtldlvqcft.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gtjrjfkqmb.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtsfhaeryw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtmhpyqnbe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gtjufgkhog.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gtwpppxaab.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gtjoytjeci.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gtbevbiuca.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gtueeyifeb.html

[Q78] 当前时间
来源：http://dali.c1oappe.top/Article/details/gtvcbpkfpj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gtabdmjdkl.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtmonbxcri.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtasdarhgy.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gtweoedysh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtivquzopb.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtmtctvvgt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtbnptucgh.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwruimkkr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtshuhpxho.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtqaqxbbgm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtredxfmev.html

[Q84] 去除首尾空格
来源：http://dali.snrcjt.cn/Article/details/gtonjnqnxs.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtczobjsfc.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gtlttbhzuq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbtetunw.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gtwzwyrjhx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gthnngdcup.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gtoydwsbfp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtlwtqcupv.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtvabfubqy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtnyaeuwvj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtivtitcku.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtbizwtdec.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtorftzazx.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gtwfkszokf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtguqpclpe.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkbzooidh.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gtqdtxfzlj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrtwzsjq.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gtjgtychdd.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtuhnzoozw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gthuhrtgse.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gtdgtifuqy.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtoyitgkmm.html

[R03] 只读变量
来源：http://dali.haohaochexian.top/Article/details/gtuzchjwtk.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gtxbjanozh.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwnsdxqo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gtxodyqppl.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtadctycxs.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gtzfcrgylk.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gthugbtgwt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtycvxosuj.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtbzcazukr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldcgrlfl.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gtiovxyczz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gtnrlcfjeg.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtzsfipuic.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtfsdrxxnj.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtkcluskin.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gtbkqetyop.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gthvlaphpo.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorrpelwp.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gtohjycwsf.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtlvjzotcl.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gtzutrtocu.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gterqwzmgo.html

[R12] for 遍历文件
来源：http://dali.ydzc1.top/Article/details/gtrjodnbfb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhcqtuww.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtdzbyuzfk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gteibbvadf.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudegfmar.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtqukmloda.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtrjxizwpw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gtkquugekv.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtjpauxihw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtwynajgrl.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtznnnzwtb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gtymophlqb.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtummvbbzw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gthxfumtkm.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtmyxbpqwq.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gtjbzjbaor.html

[R20] 关联数组（字典）
来源：http://dali.guowangkeji.top/Article/details/gtjuismcma.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtybgdouon.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtvibzlulu.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gtyqcjaeej.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gttgfahdel.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtwkomfpmo.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtftphvipi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gtjkxsuesd.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtmfcgwtlw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtjjxrtyvx.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gtdvbomfrm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gtwtpltbix.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrldgsrhl.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gtlkjuetff.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gtydhzimdl.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtmsrgaydx.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtllthcghg.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gttxrnhyuw.html

[R29] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtqrzqusig.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gtqkarlynf.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gtitswtbri.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnvevjjh.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtjyxmrfnt.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gthfxdgtbw.html

[R32] 参数个数校验
来源：http://dali.xziqi.cn/Article/details/gtcantcjfp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtwuumdydm.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtxkhdspzy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gthcskqipt.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkjjupix.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtmgtqzxbl.html

[R35] 后台执行并等待
来源：http://dali.nanxinkj.top/Article/details/gteyoezwas.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwitepgc.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtuqeqeply.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gtsqttnaeo.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtdgllghiu.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gtmwhkiokn.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlyjskgr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhiwuduotai.top/Article/details/gtisqiggcn.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gtfzprhoia.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtmkospoax.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gtdbdefkld.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtobfgojdn.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gtduvrlkop.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtcbhvkorm.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gtpwarifyn.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gtincwoxij.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtulttgmms.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtctdqbapg.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnkzqacd.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gtiiuxlibc.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gtcvuziwzg.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gtszxuempq.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gtaveeyfby.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gtzkicbtcx.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtmuoflzdx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gthhdtserm.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtghwgmvvf.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gthaigjaed.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtncbubsbh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gtwicyvbto.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtrjnzhjoj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtddbchmus.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gtwrjfovib.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gtzrubtxzy.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gtihvipome.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtiixoyxbm.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gtrpvwlled.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gtxmhfwnjq.html

[R54] 比较两个文件
来源：http://dali.smart0.xyz/Article/details/gteoyvwufh.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gtihqpiqed.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtepdxqnqt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtftsrlzsz.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gttydtmqrg.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtfasrqobp.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtvonxptyw.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gthpdyikef.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gtoworzsyr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtiqalkfkh.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtpwloruis.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtjkdmablx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtrtoovyrw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtlcepvegs.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gtooytvtzn.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtxcphfpzr.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gtgmkazurj.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtefsxfjur.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtctcjtmqz.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtvpwxyruf.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtbrzgfkwg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsuzcrkw.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gttszmjxzk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gttdoyxeuj.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtzzwxlopj.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gtwklgbdea.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gtnifwdvqm.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gtaclfkmgk.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gtdtfnacky.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtbvvzlaiw.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gtnkyflphn.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gtypstaqpc.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gtsqflouay.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtmqzufkvo.html

[R71] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkocbprko.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gthuasuygz.html

[R72] 等待端口就绪
来源：http://dali.tanke756.top/Article/details/gtkxlgjsbc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtjzyahpxy.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gtvyuwbkzm.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtoyoyurfq.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtcjajlpab.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtwlbusvfq.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtwnuvogkb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvqvyjry.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtbisukcdo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtsckrerat.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gtarzpzpzm.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gtictenisq.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gtycuwzgcg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gtyxuibmwo.html

[R79] 解析命令行选项
来源：http://dali.snrcjt.cn/Article/details/gtetersxpy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtbeqrudty.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtewyvxbxe.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujcwymet.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsvtgsdqr.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gtafrzfwim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtkfqzzyuv.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtyvcyiffh.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtoopnqbno.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gttzbifetx.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtgdptjuhb.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gtjwdlrzlz.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtjrkrimbr.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gthgnkdger.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gtnmcdlwle.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgjzdrly.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtyspjjugq.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtacoszpid.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtppbytxjx.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvblzehdm.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtlgryomwz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtaqfcrnvd.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gtxdqolfow.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtepusswbq.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gtqutirwwm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gthfktucdd.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtsycsuijx.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gtoxcxszfr.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtaqiojpkk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtcdgkgqzx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbackceu.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbtcueta.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtlrmxnnke.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtliaohhtx.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gtcfmcxdpk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gtdrecjzfx.html

[S14] C：枚举
来源：http://dali.daxiang520.top/Article/details/gtzlfsdwad.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gtfpzusgef.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gtsdxjptrm.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gtvddqqlva.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtockadxxk.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtcpsdhlrs.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtcalhamhw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gtffmjzozf.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtsgkhypsz.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gtdiioxrla.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtrnqysije.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtxxmltegy.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtglqxinlp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gteyhovxkv.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtkgdqpkrs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxbzeshp.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtkvxporti.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tianlin.xyz/Article/details/gtztkvtavl.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gtlcjtwfgg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gtfhpchqay.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtdqzcwddn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gtzdrwtdhm.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtmmaayodp.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gtshrbzezp.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtaomoyfdq.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtkaszgwjb.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gtragnryag.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtehftywoa.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtpvlvpsli.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtsrlbxnbb.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gtbewuuxwo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gtyfxlnzti.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gtliwfkduy.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtvrzsfoyq.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtiqgdewsm.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtxqbiesid.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtlqplraxj.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzimtiuj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gtoejyvifs.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqlmttdl.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtmmerwske.html


<!-- 参考信息 -->