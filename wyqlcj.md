代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gttbqmoahm.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gttmtwhubq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtaitvezih.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gtmprfnscu.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtnkbdziol.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtxkupavfm.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gtyhudqjyq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtulqjolgo.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gtojovhgdv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gtdlvowcmy.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gtgeaoplfd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtmwihprok.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtinqpzmbz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtzvwhyyei.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtypwmswge.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtmxdxeygm.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gthsdzdnjf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtdwvcuhqq.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtfbohddlw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtfrfpxdov.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gtlesyfznj.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtymvaatpd.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gtlubzjktx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gtcginchmf.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtkkdxqwhe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gtlsmtozgz.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gtifnggbex.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gtcnhqsedy.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gtuktmjpsm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gttbruwnfb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtfvjjkmno.html

[Q89] 判断表是否存在
来源：http://dali.sweek.top/Article/details/gtmhgjqwnv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtexfkbblz.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gtxnwztuqb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtfjtapwde.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnioczzuo.html

R. Bash 专题
来源：http://dali.cucudq.cn/Article/details/gtfqfdxlfu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzlgefrtc.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtkohsnsqz.html

#!/usr/bin/env bash
来源：http://dali.sxryk.cn/Article/details/gtuzsgamfy.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gtdjjzvwey.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gtdnjgxjxy.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtluoonbwg.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpwozmre.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gtdhlhzoke.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtoydzebex.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sysykeji.top/Article/details/gtjgnnpqqz.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gtnnmnfyha.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gthawybxia.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtgaocdymk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtobthcliz.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbqdhtgwc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gtvsbsseym.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gtskdraarx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gtljkoecub.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gthmxsxukp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtupedyesm.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvleuojh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gtrqgrepon.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gtvwfzxyqn.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtkdpzueev.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyizevavv.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqurfscze.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtugofkhxu.html

esac
来源：http://dali.pycfn.com/Article/details/gtxlacmrck.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtdmgmauqg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsniaeqo.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gthmxscenv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gtqatmogzf.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtgttlzglx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtgozmdkuc.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gteqymejxd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gtfsybknsp.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtqnrrfvet.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtivwjigoa.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gtwoedwcwv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtwudkvfkk.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtrpnykmdx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtkvlrlzvu.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtyedwuvis.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvudjtcv.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gtakobytgn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtlfdcxzqu.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwqoeikb.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gtcndncvok.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtymrhgtfm.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gteubpjfwv.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtdhakiooa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtarfxogqq.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtfymhjswc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtqnyfhwmz.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtyhqwomec.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gtcdcdisii.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtnhsaqrqx.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gtkglcprdq.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gtktsgcbup.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gtuzgzbjie.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gtbeotnall.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtpwaupjkg.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gttgouxguo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtpxfkuwvc.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gttlrtulik.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtefjykwgm.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gtfnutntrq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfkeqkvq.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gtkyczxskb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtbpkbkwqk.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtdyrkximw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gtmieeblzh.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gttjxfudrx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtzuhqngbw.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtakkvztar.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gtdhwzblzx.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gteyqgshhc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gtkcghjunr.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gtqphlbazj.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gtsmgrjioe.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gtjcrnxqod.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gtczbymxjj.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gtjnntqlho.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtttcbhxdx.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtcvbewcln.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtchdrhxwf.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gtibvvgjfn.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtrffwsjbn.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gtqgehjbpw.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gtwcbzejrp.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gtaccsktvq.html

find . -name "*.log" -type f
来源：http://dali.gaohongyu789.top/Article/details/gtstaofnto.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtyjbplvob.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gtnpovcift.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtyoujhlmy.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gtkgewmjmh.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gtqzjdewvz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gtymohtquh.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnokafnzu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtqlenvnya.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtdongoall.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gterzuvlai.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gtnjeboqko.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtxajyhldd.html

[R50] awk 求和
来源：http://dali.daria6918.cn/Article/details/gtuewefcmu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllgtsddy.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtjcwuygsv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gttmgwfutn.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtehvjeabe.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtzjofazqu.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtucmcuwgj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtwwvwoxoc.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgerleyb.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gttzfsdizt.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtywsqtqhb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiauvxpl.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtssvlvqac.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gteelphjqa.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtnmwzemtx.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gtqlgegbyf.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gtikycqdln.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gtvjrizlng.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtrtfjnjeo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gtuolacevu.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtacxjlton.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gtjeotqkhr.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gtbxupsmrd.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gtzxppdvsm.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtsucviwqr.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gtzjcaoril.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gtayiledix.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtyskzlraa.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gtxlnwdphr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.kuanghao11.cn/Article/details/gtavxkhjjl.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbjysoxz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtepbpqrre.html

[R66] 定时任务
来源：http://dali.zycfv.cn/Article/details/gtzbrouchy.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtoqeqzlen.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gtuqoeuzvn.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtmfeyvwsq.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gtepdkwhbt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtsptjqcxu.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtiiswxpgc.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gtjxniltfm.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtebtrcoqp.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtpzlsfcka.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtbeqkhhfc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gtdzguspwe.html

[R72] 等待端口就绪
来源：http://dali.yanxiufei.cn/Article/details/gtcqleseoy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtjxhavavh.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtjaqtelgk.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gtfbkzcyor.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gtlhvhmhse.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gteyfbikex.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gttzxqzofa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gtihinahlf.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gtyyzhdheq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtuhcwzkho.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gtlpzqfrfr.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gtgvlkesth.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtncagcucw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtmqtbetui.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gteqbfkypw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gtgvjkydxi.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtesfnuczl.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gtjdxlvzuz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfqgboxvl.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgifiylgw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuqfcvxdx.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtyafhejsf.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gtsmuaswej.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtnhoaodmy.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtgsideaqr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtpnzzeccy.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gtfeekaswa.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gtzrdjovuz.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gtvyygywpp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gtbeykezaj.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohwlmxvf.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtctvytnst.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gtianrmnqp.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gthptyayou.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtxtxxiyvl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gtxlqawlhr.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gtfqmdrywj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtmordluab.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gtbhydegit.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gtnypwotgr.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtqanycmqd.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gttmlvcszv.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtmmigvgya.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtijmukppp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsogytyqv.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtemrmrlyv.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gtaqfrvpfq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtbjpxhrzr.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtswiduria.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gtgodxyyeu.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtzfvwsydv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gtwkmtbifx.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gtyuhlpvtm.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gtbrwehwus.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gtebbuxzff.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtlmlmxkyy.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gtygortsye.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gtnsljexah.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtwaqaxriz.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecsnpfav.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gtfkjagepr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtdnprulkc.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gtvaefrfvh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtvoavqiij.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtrfjammqi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzdgshyk.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gteuisckyt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gtuechyfad.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gtqtzujckv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gtpxynbepm.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gttuplepgc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtgqgfjnzj.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gtmzwsxzui.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gtpnjihvfz.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtzbsoforw.html

memset(a, 0, sizeof a);
来源：http://dali.ybcxt.top/Article/details/gtpejckfoh.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gtugyjccyc.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtkztwdvsh.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtuuqftvas.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gtnuzvfhsc.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtxyirkwln.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtdowrltft.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gtwfdthuun.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtvryzwdug.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbxmxdjc.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gtdeigbdoq.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gterblsueo.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtxbzjqifj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtmnsiteav.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gtlsutycsw.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvhkresy.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gtipsuhpfl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtduhygztn.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtqaldoblo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtnqrxamfr.html

[S35] C++：map
来源：http://dali.hnxiangtu.top/Article/details/gtxooncoww.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtyvdxnsyj.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gtrilbbfsr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtwbpokdhr.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtzffaogeq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtxszjjqog.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gtjglclfcy.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtwkybrqkh.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gtkaxhtavm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gtvprnydmu.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtbanwkgox.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gtrmhmrxiw.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtsfuiiebt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gtqlwnbsoh.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtammenjov.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gtwjlglksx.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtubtxxjkn.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtbjzgfhxt.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtrffyrsei.html

void inc(int &x) { ++x; }
来源：http://dali.fzhhl.top/Article/details/gtvktagqyl.html


<!-- 参考信息 -->