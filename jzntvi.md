代发 wailian999

[Q76] 按天统计
来源：http://dali.daxiang520.top/Article/details/gtacnmfrpc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtgskoicin.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gtxlpqvfjr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gthcyxweyf.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtpxkpiooa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtxaqwvcya.html

[Q79] 字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gttnfkgtsd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtfxmuhwre.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gtwpojmhks.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtjxizoemo.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtzoprupbn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtcuyvlwkw.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gtmigvryea.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtdtwkfemo.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtxdzzstzo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtciwcqera.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gthaizrnkj.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtfjjiihyr.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtxwujqwjq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gtotaiahnx.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gtwoooycjf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gtkektnktl.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtyduqtikb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gteesizfws.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtocldduto.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gtwivvzfyb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gttnoyjhpv.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtztvsdwna.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gtouifgpok.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtaqfpeurf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gtiodntqsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxdditkke.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gtuqekpfyj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmuzywzy.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gtvdkhqqap.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzdddhbz.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gtliatudiu.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gtispdudoh.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gtgvmmlvxt.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtzaamdtpj.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gtowljgyyi.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gtfmfkffrc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpfwkwga.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtmytdblip.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gtoiizgobe.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gtmlgflxvq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtkfcejevx.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gtetrptojx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gtcblfhqgz.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gtvfqkzfyq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtqpollmat.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtcunmdfjw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gtqcqiicsd.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gtzivdcwyd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtdownhxez.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gtimxrkzen.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gtievgyajm.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtjyzkmnej.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gtticgdnwe.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gtbhnlxfjy.html

esac
来源：http://dali.yuxming.cn/Article/details/gtospdbesn.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gtriccbyew.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gtdllxgbbh.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gttenyxvjj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtyynmmyrw.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gtzekrvcvn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtgnhgapkh.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtzuqsfbjg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtcjgedmqo.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxfihqns.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtmdkocyxm.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtjwigmuqu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gtknrugksq.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrxpjcia.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtmskuepmq.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gthirfsavh.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gthjjrthqz.html

[R20] 关联数组（字典）
来源：http://dali.cdnleiting.top/Article/details/gtfgsomjgz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gtdtonesvh.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtvdkvqfaa.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gthqngrfuf.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtujbcffnk.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gtpioubwqc.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtwvyshaja.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtkmxrpaya.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtfxevztor.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gturrfgeex.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gtakhngsvw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtvextixju.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtlpjqxbiu.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gtmnporhmf.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtitzcflgd.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gtabcabemv.html

[R28] 浮点运算
来源：http://dali.xinyue.icu/Article/details/gtycjbijtx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gtecgpvcik.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtrksbuntt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtpapoxniv.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gtdxxkdbqg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtaacfdcat.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtewktjxvd.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtymurmaxd.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gtolauizro.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtcirpmgny.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtoxxcaats.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gtrzfubjhy.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gtszhvhwco.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtmbzzugxc.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepoxcxsb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtrlvmnlys.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtdskxtgzt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtqvxcwuyb.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtmbqvjldd.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gtldfbawik.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtekohwynn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gtmianrwws.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gtctagumtj.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtzthnurrm.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtgttqbstl.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gtsmexsgde.html

[R41] 丢弃输出
来源：http://dali.hnxiangtu.top/Article/details/gtmytymauf.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtbrktjail.html

[R42] 输入重定向
来源：http://dali.tian-w.cn/Article/details/gtjtoayhtx.html

wc -l < a.txt
来源：http://dali.ivvv.top/Article/details/gtlhlljfej.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gtgxxrxrop.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtzcxtynho.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gttermwdbl.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtwmoahtdz.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtprvrntun.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtpxsxfirl.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gthryhtgvn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtgqmagcat.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gtcmbxvoap.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtzcxftopr.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gtyhwlfetx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtmdzaactm.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gtffhdqzpm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gtepgapcji.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gtxtholxac.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtbasupjom.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gthapailtn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gtjgqjvwqy.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gtsoxscbrn.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtjwdewwqh.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtkaonvvqd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtfalvmhcr.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtmzqhvrvu.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gtvbikqick.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gtqzocpweb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gtszlrudxj.html

[R56] 远程拷贝
来源：http://dali.snrcjt.cn/Article/details/gtqryazqdt.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gtftrulfax.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtgiuzotvv.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtehbqobza.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gtrhavtier.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gtxkbxwkyr.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtqbjuzcoo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gtudiygbls.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtujdlursf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtkquyvegs.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtjwygzvgd.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gtaadytafi.html

[R62] 找最占空间的文件
来源：http://dali.shuidangran.top/Article/details/gtlpmabxkg.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gtnvlhwwaq.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtsrsyklgc.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gtslmujzka.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtayhunkmi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cashguo.top/Article/details/gtuzqfizlq.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtjxdulbch.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtmaiqxiue.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gtdnymhvzj.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtqustusie.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gtgfzplhtg.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gtvigkfdfu.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtsbzwgapi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gthudeqogx.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtzsvvsukp.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gtihnucrhr.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gtddjvssbe.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtwdejnfkf.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtudjdiuhg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtzuodkbwl.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gtwlcjbzqe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtyoqjamvw.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtgwuoxdsc.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gtphavhscn.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gtqbocsdlf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gtejgmafaj.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtlvgcfgxq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gtizpprbsn.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtkoyrjphi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtufdvllrq.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gtuoidiymy.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjlhmihl.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtqvnwyraa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtamcyuabm.html

[R79] 解析命令行选项
来源：http://dali.cucudq.cn/Article/details/gtlgepnrwt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gtqqnfgtcx.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaoggrms.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gtvwnrtqyj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbkmgulpk.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcglnzpr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtewggtmqq.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gttztivgve.html

#include <stdio.h>
来源：http://dali.jinqigfzy.top/Article/details/gtajeubxar.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gtmfgnnxnc.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gtqzzrhjvm.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gthmpbpbar.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtbtxuuvga.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrszvbbuf.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gthuvaqfpz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtyqcmbkud.html

[S05] C：字符串长度
来源：http://dali.meibo888.top/Article/details/gtmswsimqx.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gthfjeikmm.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtrejsvesp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtvreugmbw.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtzjyhplty.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtqnfwmanp.html

[S08] C：动态内存分配与释放
来源：http://dali.gaohongyu789.top/Article/details/gtpiaobarz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gtqqvzmhnm.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtsuweiacf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtiksxubqp.html

[S10] C：指针与解引用
来源：http://dali.snrcjt.cn/Article/details/gtwzjxqlsm.html

int *p = &a;  *p = 5;
来源：http://dali.zhengqikj.top/Article/details/gtqblzycon.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtanfhlvck.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gtqnaqcynn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtpwylghel.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gticsvbdhi.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gtfbzhdrvo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtusfvxctg.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gtidnljpht.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtsrbposwu.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtporhjxnc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gtzvuixmit.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtagfkemqw.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtglnwsrtv.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtpxeroanl.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gtvsufdeez.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtznudiuxs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gtbkjdeoal.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gtgjiuzfck.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvsplpkg.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclcablnp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gthmjinqce.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzfbyfzq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gttxwdzvqv.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtjldcjhfe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtexiubhsp.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtqzrosvve.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtxownyuqc.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gtqgypxhuk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gtxzggbbbn.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gtvfkpplve.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtelzpsire.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtfwtefwvg.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtzojwnquf.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gtvzbgfand.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gtztejpuzn.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtqoqoderz.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtnjortknb.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtnqtiktga.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtaqtykiri.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtpsaawoqo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gteknedulg.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtoaxswukw.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtwrcakifm.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtlsuariec.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtnthioihv.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gtqlyesqhv.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtjtyxnumd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtogegvpwn.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtsfgdvgcr.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gtzuyrgojf.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtrpsbmkfu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gtzzmktwnn.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gtsesnpund.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gtgqwwfxty.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gttmqnuvoy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtwrziskyd.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtcaphakze.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtiehlrnwt.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gtzksbpzyd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtnmqiiomc.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gtenjahefm.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtsccdcpfz.html

[S39] C++：自定义比较器排序
来源：http://dali.guowangkeji.top/Article/details/gtkcgfsoeq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gtupkaunur.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtervkbmfl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtgppzsmam.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gtfpinllgx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtypmyybza.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gtejxlytuy.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gtdtasvrpc.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtrvxxhxcu.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gtthimixcq.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtjiqkwlwu.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gtbkrisxsj.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtlwnmusab.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenjidiqi.icu/Article/details/gtqmdtpsex.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtdcmjxxxo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gtktsrimru.html


<!-- 参考信息 -->