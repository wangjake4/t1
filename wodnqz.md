代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gt2xgcerast.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2vithfnlq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2iornifqs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gt2xxvowzit.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gt2ijsuzlfc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gt2ytftjlyj.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gt2epmijuti.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsdnomur.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2tkhqburi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cxugphyl.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gt2ahhcynuj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gt2fgkqgsnd.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gt2lgdtzsmn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2fpohecxw.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gt2vfuphsoz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2khqukpwi.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gt2wijnkdod.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2beylegtl.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2rfwthdhe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2aopocfdx.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gt2jgxpiitk.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2skbskzah.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gt2iqmutwzi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gt2uifodnet.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gt2tydcznaa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gt2zpztciqk.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gt2wkoigihu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gt2qgpckykq.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gt2dectzpqm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gt2ejrwdnnr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2mxgwgnpo.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2zivxngdl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pztgntuu.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gt2ypiimuvt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gt2ajtrcber.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2fddznncg.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gt2apdkmkui.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgwxuaiu.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2tzwmcaoi.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktwmmchy.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gt2gkkcpnxe.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqsymszl.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gt2fjzweacz.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gt2kfdrfbzf.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2idqjccar.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gt2qwpwrwuk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsruwocr.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gt2sujczhoy.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gt2suozrhsd.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gt2duutepzs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2cpafrura.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gt2ducwqbcb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2fmzbetco.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gt2wmrsenvz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gzhubu.top/Article/details/gt2idyxkdmj.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gt2zlqhfhvy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2wgucpnbu.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gt2yeconpxd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2fojzzvzm.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gt2jdzfxyjw.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gt2affglwtw.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2asaudyny.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gt2thfxpfcr.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gt2zmchtbsg.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwbcvygh.html

[R12] for 遍历文件
来源：http://dali.ydzc1.top/Article/details/gt2pndaailc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gt2lnhjbfpj.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gt2ytlghvag.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2ekpqncoa.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gt2ogdkhrbx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2pjjpztta.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2pllwxenb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gt2xcbnqzbp.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gt2ihvndhib.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gt2jvhftboh.html

[R17] 数组定义与取值
来源：http://dali.wangdashe.top/Article/details/gt2gfviduxo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwevuuhp.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gt2jkwzsous.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2makxezjs.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2diblszfn.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gt2duebrmnz.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gt2ivoxaozv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2agakmlfs.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gt2hhlyqvqr.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gt2rschyesm.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxtsnfcs.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynjljbns.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gt2bhshpghd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2ltqsimmw.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2qiplwyya.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gt2vdngyjal.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gt2rovumjzn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gt2mdgwfftx.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gt2nujctnuf.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gt2axwknnlk.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gt2lkcntaru.html

echo $((1 + 2 * 3))
来源：http://dali.fzhhl.top/Article/details/gt2ehgarzdr.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gt2ymnyxlkb.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuanzhike.top/Article/details/gt2jvwqlohb.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2exftqoaw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gt2mzroakdz.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gt2xqhfotfc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gt2ebpnweeh.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gt2nzvyfdwd.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gt2ilzycuof.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gt2kuwviurg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gt2gwkpxkff.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gt2luteidib.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gt2ctmeywds.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gt2nlsbefkg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2wnoyibmg.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gt2hlbrspjb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gt2befpmtxt.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gt2fdnshlvb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgijucic.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gt2kcksneqp.html

files=$(ls -1)
来源：http://dali.ivvv.top/Article/details/gt2gcawhvew.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gt2qnilsang.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gt2ijumscgr.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gt2jbauklod.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gt2inrqqcym.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gt2jhkfkrnv.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gt2upbntjfq.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxvsdqnq.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2otjacegc.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwzsbhfl.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gt2yxqtidyb.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gt2nhzzmzzq.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2bluzvsky.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gt2owbxqkgk.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gt2kybvgooa.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gt2wucmvyqx.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gt2pmwkluuf.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2enubnbnp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2hvrfvxra.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gt2cbkwcdtz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rknzzlis.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gt2gutsquyh.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2yjhsmspm.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gt2cdzprenx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gt2dmpxxkpg.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gt2uflxjjik.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2qzxpvhle.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gt2xnlredse.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gt2wpuawkuh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gincsqwl.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gt2sewsyxtg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhongyouzk.top/Article/details/gt2tpdchbgh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gt2rnrzrtls.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpxhozny.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gt2qbtojmfh.html

[R55] 压缩与解压
来源：http://dali.quarkkingdee.top/Article/details/gt2wvfnslpy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gt2juumvjkq.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gt2bmpknenl.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gt2rvgqscic.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gt2zoktguqd.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gt2lhapgzgu.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgblgois.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzyyhjyo.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2vcaxakda.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gt2iipnzybl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2qklvsrml.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gt2ptcqzejf.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gt2vlxalemz.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gt2shotwxwf.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gt2pcshlzbr.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gt2erttaooe.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gt2njhiupdy.html

free -h;  ps aux | grep nginx
来源：http://dali.xziqi.cn/Article/details/gt2dgvdnwyh.html

[R64] 结束进程
来源：http://dali.yongpay.top/Article/details/gt2nvdgnaie.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gt2risfllmi.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gt2gqcgqaqc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gt2hbnwieml.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gt2sknofanf.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2ixmhokvm.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gt2nfusobfz.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gt2dmmxxhmu.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gt2kkvvnqgd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gt2neapbhcz.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gt2zrxezmdc.html

head -c 16 /dev/urandom | base64
来源：http://dali.shuidangran.top/Article/details/gt2fzaxwczi.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gt2qtidcbda.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gt2ssnakffq.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gt2pmldbqon.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gt2damsacsp.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gt2vljsrery.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gt2hzqugfxc.html

[R73] 分割大日志
来源：http://dali.meibo888.top/Article/details/gt2tbhxzmbx.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gt2msospedm.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gt2ydcvmwzn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gt2hwzwabfk.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gt2ejpuzqis.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gt2pnxupiny.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gt2khgvxsni.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gt2xnoibtnx.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gt2mecicudk.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gt2gvxpltkp.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gt2xhtdepir.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gt2cmqxljht.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gt2jutnrjgr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.vqdsnc.cn/Article/details/gt2xytsjcfr.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gt2qsoprdvc.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gt2tbszlest.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2grxblbrm.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gt2vudywkda.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2klvqgsjg.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2mptfyrpn.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gt2zgsqwwve.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gt2mkuaksru.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gt2eepixtei.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gt2cxgyxuqg.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gt2yhzdwulm.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gt2ttvkieur.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gt2tyknynti.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gt2vquxeirz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bukginnp.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkzduorl.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2lyvxrhgs.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gt2buiykwxr.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gt2dqpbwrfy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gt2shsgxjea.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gt2hkqhdkdb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gt2oexkfaoc.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmeufdwm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gt2ofmawegl.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gt2qcspsfdk.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gt2lhhewlhe.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2lopcjrbu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gt2irukpveq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gt2xxaaepqc.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2nfwrhmjl.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2yyjidilx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cheryme.top/Article/details/gt2dyitgmsm.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gt2ueiuhwel.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gt2rxzegdoe.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdyghxmm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gt2evsorsmf.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2thfufpom.html

(double) a / b
来源：http://dali.iojbl.cn/Article/details/gt2awvlfegf.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gt2fpwhbjgv.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyiwgoxj.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2wviobunp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gt2uzhjwyci.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gt2acwtpbdh.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gt2qxroajlt.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gt2ggavttvb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2fruwuvvc.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gt2khfvdatu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2eteujhii.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gt2vbvndbgi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gt2vzggkhop.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gt2rkezbkqu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gt2plhqgipl.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gt2lclgrvaw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lscmroys.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gt2zlypjveu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gt2ecphsyee.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gt2ejgvfipp.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2rvayklem.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gt2rxwrdcew.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gt2sknaxaup.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gt2kkhjovvg.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2htkwehkt.html

[S28] C：静态变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2tqvprack.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gt2laidonyp.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gt2pyosgrqy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gt2meaergyw.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gt2rbbikvno.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gt2ofkhgpbq.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gt2tizaqgvw.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gt2ootprnaa.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2jxzkhqwe.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gt2pjkavhzu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zedbtmqv.html

[S32] C++：字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyhlbsle.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gt2vgxekgvl.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gt2dtfqnhga.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gt2uvqoqjcn.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gt2hhtqdjux.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gt2bcgqdctq.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gt2fpblqyrl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2thiizdks.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gt2psszehog.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2larbiykz.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gt2slnldgsj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ppjwa.cn/Article/details/gt2towatmcj.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gt2mmdhmqrm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2mslvoudn.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gt2hfyarhaf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlwbzgyl.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gt2fhdegayi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gt2izxoomll.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdgxwoc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gt2nikjdolc.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gt2gdimljsz.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gt2apqksupv.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gt2uebekgfv.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gt2tjeatbpl.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gt2dfrjrtfg.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gt2uxqqcmxk.html


<!-- 参考信息 -->