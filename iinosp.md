代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtogrmgxsf.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtdhdnqhfc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtboarrcsx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gtndpstggu.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gtjotowaba.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gtxvtthxqo.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gtinhjbkqz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gtlpesruwt.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtuzqnrejq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtfhjjvbsk.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwkofcfd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gtqggitzat.html

[Q80] 字符串截取
来源：http://dali.gogol.net.cn/Article/details/gtztufwbvl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtkfqawgfs.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gttidwyrdt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gtkquskpsy.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gtfnkubhdk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtnavfxnbb.html

[Q83] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtybzgejsj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtwtxnxlaa.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gtvuwhrada.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtefufqmza.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtykamxyzp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gtyujizwsl.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtgslryrbu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gtoxgwqzsm.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gtyktwgmke.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtsnskfzef.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtapdmlnww.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.kuanghao11.cn/Article/details/gtvwcixajh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gthxzktgki.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gtsdayisfk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtwlwpcbyo.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gtgflatsis.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gteayolbbm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtifyrzkbw.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtadzggsxn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrlgxxjvg.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtroykxdig.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gtjidtzgln.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gtyingtbvj.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gthvksqjbj.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gtleudplye.html

[R03] 只读变量
来源：http://dali.ydzc1.top/Article/details/gtpwjogqjh.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gtullijqyy.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtgapvhaft.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtegooqqox.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gtllmgtdtm.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtqgkdkdxr.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gtvvjrhoqu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtvfuofjkg.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gtimuglyky.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtyeiskswp.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtpxjblxhz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gtpbzgtxqr.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtkifbeupz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gtrbsekdar.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gtevhdftao.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gtuyfcqivn.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gtkkkbevmf.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtsyeiwgwd.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtonezxhrf.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtryphmgyb.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtbtsvfoce.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtgpmzgvno.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gtoynthofe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gtgziuwyuk.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtjknkcglp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtptdagftj.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtwyzrbube.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtduooumfm.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtgrnvwyhi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtabradsld.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gthawhafmb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtjrnjwsvd.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtcwmkroom.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gtywsnouic.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gtioatseiq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gttojthnfj.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtfphrhpdh.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gtkzgzbuch.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gtrezcbebj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gtjuzhsckr.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtoceyzuyx.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gttbaphtgf.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtviwjfwoy.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtwaueepla.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtpryvyyhp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gtvwulutxg.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtnhojckiv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtbtiuacnu.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gtjlftbuiq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gttwsobpmz.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtjeifbxmc.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtcsfdxhfg.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtnyscidgz.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gtpzzywrhm.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtfdurhvku.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtqnppxhah.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtzqeryxij.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtqmzbaaxp.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtsdlnzavn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gtnahzzwwz.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqsustad.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtqxnuscdg.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gtdqkeseaj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfcxmxjq.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gtnagyrwwi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gtnbgpfzih.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtsvjeoiij.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtkkjnxzqb.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtzinhszlw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gtpcehgvwc.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgxfcfdc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gthcgsplux.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gtnftvugfw.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gtypqxzibx.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gtxivozmgi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gtwuhykloi.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gtqivyyzxw.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtlezqjbpr.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gtrcvtflgk.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtqvjigcsv.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gtyitxtjdk.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxsoovsh.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gtfxsahdlg.html

wc -l < a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtvhdzupvl.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtnsesaztc.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gtgdddfreb.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtwfzzyfrm.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gtqbqkqooy.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gtrjrcqrgj.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gtyqushliu.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gtanjugrap.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdkymxue.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtxqjnorzj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gttoyqbsxn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gtmbcpkbcx.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtkwvccsql.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtknsavjer.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtzehcwult.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gtjzxqmclb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gtgahxfbef.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gtbzkneifb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.vqdsnc.cn/Article/details/gtkshgggop.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gtkswnrgvm.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gtyxolqler.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gtpquxtogn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtjyukafxy.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gtrchpbdup.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gtdrtqlbmr.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gtybdvdqbu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtzwwrftpg.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtjnjexprl.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gtuqrfwasb.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gtkqysgniz.html

ssh user@host 'uptime'
来源：http://dali.sxryk.cn/Article/details/gthdbmqczr.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gthpqvjwbg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtaldpckws.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdofayeou.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtzovgrdhk.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtkjzypzbx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gtezxtffuk.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gtgpdspord.html

df -h;  du -sh *
来源：http://dali.jianghu66.top/Article/details/gtdenybect.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtfcprmlbj.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gtcipanqte.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtshbcllhh.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gtafxxynjx.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtcwvlohom.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtufrhfjms.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtnnyooumb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtgxymymph.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtkmdfovtj.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtoulcejuj.html

[R67] 生成随机十六进制串
来源：http://dali.hywenlv.cn/Article/details/gtlfyqtarg.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtxeywbnhu.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtvvursvoe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gtsppcrdmk.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtdrlkdilu.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gtcsnkmzga.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gtwnkgoikf.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gteyhbszck.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtcinhaonm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gtdguzddfy.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gtlmfmdykf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gthytzniqf.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gtxaxarcsc.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtkmofsrpu.html

[R74] 批量重命名
来源：http://dali.meibo888.top/Article/details/gtfwnoxbha.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gthtwmuysb.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gtxgehfnae.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigfzy.top/Article/details/gtafdmfvsl.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtubobgpzc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtvlovtykb.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gthxgnoafx.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtbmtchfmm.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtovcyxsko.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtybsvlwpn.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtarjnrnco.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtdsyoufcy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gtyqcunikh.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtxmkpgsnl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxojsbkla.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gtpgicrdlu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrpjegrro.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gthlyovuud.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gtosqbmflp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gtognunffq.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtrvsbmxxc.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gtbpnympdg.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gtlprvsrlc.html

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gtfbshfprp.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtlqbamqeb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gtowwavpjk.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gttoiwvuvt.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gtgxljuvlx.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gtmozyuxbo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtbionvubl.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtfndxjmoy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gtszrseyqw.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gtvkwhpcug.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gtqvlofzco.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtbchesdyf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtlvzcvfui.html

[S10] C：指针与解引用
来源：http://dali.yuxming.cn/Article/details/gtxchhxrju.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gtkzkkgwpb.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtkasahjef.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtuaterbxd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gtrdjehgbx.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtwsffuwwr.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gthbxifwmg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtwrvapgdf.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gtsasvsuzg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtylwcqgok.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtezlotesx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaezsrtb.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtcjfromwl.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtdqqzacfl.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gtvlmssfbo.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gtlsecyexc.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gtwpmoehyc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gtesplyewp.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtrcgrsvae.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtewjjblzk.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gtujyseejt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtrxmqmvpq.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtkijekwae.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtopyvzmss.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gtnnplrzjs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtuezoptay.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtsotnapwt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gtblgsktrb.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtqraqmbdz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gttqdbuujy.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gtgpnenopo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gtugciyjiu.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoqnpswk.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtgxeyjfpr.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gtkatlggzh.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtxgygmhgf.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtreuzvfrb.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtmoklvlob.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gtentsahig.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtjeitzopg.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gthzfqpxud.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gtwfrfzoqc.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtpllsoyuw.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtzvialaoq.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtishmmobr.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpaeiwhi.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtevlevpjo.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtsabjkzlj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gtedfbbrpp.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gtwvezhrhn.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtfuyqwylt.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuakmfbml.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gtxpdtgplu.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gtlmpblcsd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gthyzystkt.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gtgcqcbwiw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtfpckszay.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtqtjdjblr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtxjptlafh.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gtynpcliop.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtnygaocdg.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtovnudxkr.html

std::sort(v.begin(), v.end());
来源：http://dali.yuxming.cn/Article/details/gtlzsaxkvd.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gtfydzllur.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gtimnwqqay.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gtrmrsliey.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fzhhl.top/Article/details/gtvrzylgoz.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gtaasabopl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gtbcvnqzuf.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gtmkwqexyb.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtyijwfnjk.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtakcfemhk.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtuvgmblzs.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gternrrbuz.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtptgdadmu.html


<!-- 参考信息 -->