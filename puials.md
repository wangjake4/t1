代发 wailian999

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtmibmokuc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dianchejie.cn/Article/details/gtlvvcfnpr.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtummqbzvv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtjfihivlc.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtmwmlwbkf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymckswus.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtmlifcjut.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gthwuvolah.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtssehomio.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gteivfdfdw.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtizzaqfad.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtrvttnibp.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtnrxbphlq.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbvqucsh.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gtzjgkuhex.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtivlhlipg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gtsqlnhkve.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtdmdujllt.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gtujlefmfp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gtbbqgcrov.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gtapccllbz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gtqtrbqzlc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gttmvrbqne.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywhrouxw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzttmitm.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gtmlkpeygt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gtldhypwxl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdvecpfrj.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtdjznnuix.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlozmdhmw.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gtrbwzosgv.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtwacmxror.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gtrzwnpzpw.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtvcvglxst.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtqeqihxnl.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtklltospp.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gtshrngggy.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gtjdtckiuq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtlpkmwlqe.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtqoburrqn.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gtyzvtomtp.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gtikvvoyez.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtidjplyxp.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gtcvhewchi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtpsafqklm.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtrgxvxpie.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gtxlrmoakv.html

[R09] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtvtlvjonm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gttibyczap.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gtbwmbbkgp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtcizflgig.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtcpuoxmdo.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gtqygklmgb.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuycuhtcq.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gtiyvwfqfg.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtvngypaqz.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtugjmwglv.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtekxpfpvv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtsripbgqp.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gtsnjuvvlc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtzwgymzfu.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gtcbalzryv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtduwbpdnv.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtjlnpbgkz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtnxpeaxkg.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gtqrbncdyz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtclxfskfm.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtfcjkdlli.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gtevohtiib.html

[R18] 遍历数组
来源：http://dali.yj20258888.top/Article/details/gtzjrkcwhj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gteduatffe.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtlzbdjzkw.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gtbxvyzeix.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtaxugcsxv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtcbletvmt.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtvtaezxss.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtvapzaczj.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigdayind.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gtwazogmmw.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtxzfjvxdr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtzntluiiz.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtfyzrjvmv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtjcvfgcvg.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gtcufecodp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtwzpmntog.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtbzyqgdgy.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gtbqdzjktk.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gtfqtspphc.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gtrikynyyk.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtqkcslixj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtehtcvtfo.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtohslbfrq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gtctzvqcbt.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtfhjtmcxm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gtoolrtmpv.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtsromlijz.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhhnofbw.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtohgdcafg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtovxlsezc.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gthjhvdzjg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gtealeggaw.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtsjgwxpxf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtudwrxbwe.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gtiqfeihem.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gtejayxnoo.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gtrnbwyile.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtmawvzvmw.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtafdhxmzc.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gtlmeolelg.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gtbodiaapp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gtwfhbyxbn.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gthdndlizh.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gtathvwtdd.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtkqqmlsyb.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjbczaog.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gtsecoplyq.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtgnhqpabt.html

[R42] 输入重定向
来源：http://dali.yj202588.top/Article/details/gtlugtnnnu.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtvcazcgqb.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtbgflyvur.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gtgamerfpv.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtxqswobbk.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtcyksxxwe.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtdvjranpn.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtjtnktlwc.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvhpdpcr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gtspbpkefi.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoagvzlbw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gtreuzzbcx.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtkhiywmdh.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtggrugshd.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gtryqnwkve.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gtumjfkgyf.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtmpvjohba.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtbegkrtpt.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gtmpixiflg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtbwkcumlt.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gtpaotnwsn.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gtrhoianav.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivtjmgle.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtilbojewk.html

[R54] 比较两个文件
来源：http://dali.havefunace.top/Article/details/gtthsqcair.html

diff a.txt b.txt
来源：http://dali.jqgfzy.top/Article/details/gtcofoqeup.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtwqssdxrg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtitfnyied.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtyrtbktmj.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gteszddlay.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gtkxirnlna.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gtsemelrpp.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtngkznddq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gtmrphyosf.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvvrlvsp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtcvwwzckq.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdvltqso.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzleumpx.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtpmjkypvh.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtufyilofs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gtansqpdgc.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtzbeiioka.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gtpnvgsmoy.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gtnqvdwzqm.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gtzgemkuic.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hywenlv.cn/Article/details/gthcsadnzc.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtzxopgtmu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gtjzadhgaz.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gtevdjfcir.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gtugtdiksd.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtsxcnuyyl.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gthefjuzrs.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtblaibjpy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtkeoxgtgk.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtclgddwhn.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gtzreobvxb.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gtmdxlqovl.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gtazcmzcad.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtniyomjvc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtonstggkb.html

[R72] 等待端口就绪
来源：http://dali.hfpthk.cn/Article/details/gtpaotbeuy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtpybrctfz.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtxadvxfdq.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gthdulywhw.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gtbzgebjfv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtwbpkooiy.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gtgtejuyjo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gthjzhdyyv.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtrjnlnjqf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtzybrcxbr.html

[R77] 读取用户输入
来源：http://dali.hywenlv.cn/Article/details/gtdolzpfdu.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gtvovtkdgj.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gtwlrcpybz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtvqkbhyab.html

[R79] 解析命令行选项
来源：http://dali.snrcjt.cn/Article/details/gtnaidbzng.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gtnsvmnbim.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gtkytzbfpt.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gtjosfvnpy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdjcejme.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gtztkxjqsv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokgqwosk.html

[S01] C：Hello World
来源：http://dali.xylfe.cn/Article/details/gtbuqtgohu.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gttbznfoxi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gtwukzpzie.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtmlzccigt.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gtyualgwbf.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwrqqxan.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtjbqlkcuy.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtnjmsokpj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yueranfly.top/Article/details/gtgfyierey.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtmscpmrjc.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gtlhulsvtz.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gtiwlhvfzp.html

strcmp(a, b) == 0
来源：http://dali.daxiang520.top/Article/details/gtwtlrbhtl.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtipcjmehx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtjpmyxrji.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gtrvkzxpdb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtsjryrkvu.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gtrirzxxex.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtnvcftpge.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtjwpsvksr.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtkptcjjis.html

[S11] C：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtolpcxrfn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtcngadqae.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gtwlxlcmhh.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtpocwrhiu.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtjoxaaohp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtcleqvubj.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gtxeydwdcz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtmhwlniaa.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gttjmzbzdc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbhouyll.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gtazpufcuq.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gtzqwjaulr.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuttuyci.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gtxmcbynuw.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtreclhocu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtjpeqnuzr.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtwyfszjea.html

int main(int argc, char **argv)
来源：http://dali.ivvv.top/Article/details/gttsinyxlg.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gtkhmhgbji.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtufdryuet.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtvievextg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtnpfjfnzf.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtgbwxkvub.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gtyrklkduo.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrtrtknr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gteqlxinbb.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtqdkzmqyn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gtcbyooscs.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtcmfchnnc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrsxaqvc.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtwojsotjv.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gtcjrrmxfj.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gthrlkamdl.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gtyvzvqzco.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gtfulpqhwm.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtzrdvhphn.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtaurptvcf.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtyvvorjpl.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gtquhtjtqc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtebdvcmfh.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gtfmpylret.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtacgkbkqf.html

#define X_H
来源：http://dali.ivvv.top/Article/details/gtzvniovhy.html

#endif
来源：http://dali.redwolf501.top/Article/details/gtcwycambo.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gtjaqqlhwz.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gtboqosfwz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtpxoodogf.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtvartwwjc.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gtrzecjiss.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtpvvbulfu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtwkfajjen.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtjteymovl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gtrxcxlcri.html

[S35] C++：map
来源：http://dali.andypj.xyz/Article/details/gtztcxmhih.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtcndveujq.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gtexqhgwgi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtxhujkdvd.html

[S37] C++：set
来源：http://dali.hongshengwenyu.top/Article/details/gtojrymgzt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtgxcjomix.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtqxzhjugh.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gtfqwfhyex.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtihnklmtp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtsbbcrtje.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtqbniotio.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtgqsehizs.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gtsfnyypmg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gtszikholz.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gttwwwmkxd.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtfetjyiqe.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gtsqadtrxq.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtwlyppexr.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtbwjsuywh.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtytvfzfwk.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbrxamnd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtmbsjsjpy.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gtqdxqiwnu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtgtykwyof.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gtdlrthvyr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtycsoenhi.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtprxkwkoa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gtdkgwispr.html


<!-- 参考信息 -->