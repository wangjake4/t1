代发 wailian999

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gt2eibuyjbw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gt2dzhaspxz.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gt2fvlayfpd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gt2tkgsntlx.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2cnkletco.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gt2thmfvuml.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2eofpffyu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gt2enchvpaa.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gt2pntglpza.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2nbxjvmsn.html

[Q81] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gt2xykpylkc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2zuasgrwb.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gt2mdrsvvnk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2anqxhmab.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2lyhvbnzu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2temyzmjh.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gt2rxdcjzie.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2kzkovpif.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gt2mgmqwusa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gt2hxfivczj.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gt2yibazxez.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gt2svymzhhs.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gt2yxfabxjd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gt2stkzhyii.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwuegioi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gt2fgzakkgj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrelklor.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gt2hujpnbzg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhgthysy.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gt2unyvpvry.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gt2vplaiqmb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2muvjxiki.html

R. Bash 专题
来源：http://dali.meibo888.top/Article/details/gt2djfpwobr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2kwuofwao.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2intuldfb.html

#!/usr/bin/env bash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oantrszb.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gt2lbihvtku.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gt2txpkqdsk.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gt2ewztwaej.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gt2xybnjwlm.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gt2niprpnou.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gt2bdjrqlll.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gt2mpdsbisx.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gt2otkdikxz.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gt2gbclrbkb.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gt2vhulqmag.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2storuuej.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gt2wjpdbmhv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2honapzbw.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gt2foubgyym.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gt2nrvchhkw.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2hensziih.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2fgwbhrfu.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gt2hvkoaiaz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gt2lqwdyvpr.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gt2yqvruedx.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gt2hkjbzhjq.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gt2xkokkdrn.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gt2wqrxgiyg.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxjprxkv.html

esac
来源：http://dali.redwolf501.top/Article/details/gt2ylumtxam.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2lrqdghlo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gt2rteqyvsn.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2agcheplh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gt2hndsxthn.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gt2pmvbloks.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2ujdmlcya.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2vwytdfub.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gt2dpklevmd.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gt2gfngkins.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2vtklsahq.html

[R17] 数组定义与取值
来源：http://dali.yj20258888.top/Article/details/gt2xbpvclkj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gt2gvafsigu.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htenutqs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ouegmiwx.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2khzpxuza.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2eositbat.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gt2dpwfnfvr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gt2ybaierol.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gt2vfxngcua.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gt2napfxmqi.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gt2voccapot.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gt2tjdiqpes.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2tzlqxpky.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gt2zwjkusbp.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gt2etiuqxzk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gt2xyjqsnkj.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gt2tezkvnsh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gt2kxraghfh.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gt2mfhzootc.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gt2fyqggner.html

[R27] 算术展开
来源：http://dali.guannengcc.top/Article/details/gt2cpwibyvv.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gt2megqwwgp.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gt2amtmxthk.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gt2jwoxxcgw.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2zneibpsy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2baawnrgs.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gt2oasbegbs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jyoumei.cn/Article/details/gt2okmhcmix.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gt2oamzcott.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gt2apxkyqvk.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gt2whhqmaus.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lncizivk.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gt2cffyyzqh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gt2zldkuprj.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gt2sauhffjk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wttstjzw.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2vcstccpa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcagdsjf.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gt2qfatsbaf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gt2wgrqbvmk.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gt2dysyjkuc.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfmiavle.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gt2yicykmhn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gt2hpkyaola.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gt2hgsbhlwj.html

cmd > out.log 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gt2bpvajxkt.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gt2zmoafvph.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gt2zhuudnfb.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gt2utgisejl.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gt2drnflqlk.html

[R42] 输入重定向
来源：http://dali.sweek.top/Article/details/gt2dfaquype.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gt2dgofuyge.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gt2bpdwlcqq.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gt2zrqarqzs.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gt2hsdrkeih.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gt2cfrbfoju.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gt2uohgdqde.html

find . -name "*.tmp" -delete
来源：http://dali.hfpthk.cn/Article/details/gt2wcixhbxq.html

[R46] 递归替换文件内容
来源：http://dali.gzhubu.top/Article/details/gt2tlkcvzav.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gt2sbcniovu.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2qywpekvt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2ulhrnnqh.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gt2xxcctiwz.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2aaooscgp.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezrwlhrf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gt2mtfretam.html

[R50] awk 求和
来源：http://dali.kuanghao11.cn/Article/details/gt2orednaje.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2bayorzsk.html

[R51] 排序去重取前几
来源：http://dali.zhiwuduotai.top/Article/details/gt2stotwpph.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gt2zkdgamjj.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gt2xddopdta.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gt2fxxvdchl.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gt2sjdkogge.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.iojbl.cn/Article/details/gt2kppapveq.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkxttpnn.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gt2rajnxctn.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gt2psxzjvkw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gt2yiedtiao.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gt2pybypwbz.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gt2stfvrzqp.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvqcafmv.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gt2lfshpmil.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gt2rhyiizus.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gt2fathbxvp.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gt2lbxfxoli.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gt2xzdlxcpp.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gt2wpjhyshf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gt2eiiqwzzw.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gt2mymlqroz.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gt2rdnmdjec.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gt2oofgbplp.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gt2znxitshu.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvttrnxw.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gt2zvcxkfug.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gt2nukcrmyu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gt2fuwlalgq.html

[R65] 查看端口占用
来源：http://dali.cucudq.cn/Article/details/gt2kjiazjts.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gt2buwaizjy.html

[R66] 定时任务
来源：http://dali.fengsongda.top/Article/details/gt2agivhwyf.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gt2plxzwgpy.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvclnhvp.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gt2anrahwcv.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gt2ttrkkeis.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gt2rjrmadxc.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gt2wtmpsehm.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pyxlqhnx.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gt2rwrjvobo.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gt2mpegjiwm.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2qqpwpnrj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gt2hcpxuwrt.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gt2bbtcvsao.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2myeksijm.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gt2wsnmykmw.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gt2ouxzxfgk.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gt2tidlzklu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gt2tleiqups.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gt2cfgtzcbe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gt2ndndhhgk.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gt2mdlvuvoc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gt2dsgjrboe.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gt2xskwcrlu.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gt2djernjyg.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gt2xenxnicd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gt2pqqzhbqg.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gt2bwhktayb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gt2biukgxim.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gt2qdbzfzaa.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gt2bnzqczcv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2pjoclvlx.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gt2hzwzeeoq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jfmfvmdd.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gt2duxtexoq.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gt2bkbqavtv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gt2tbebxkcs.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gt2zzzksgom.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gt2jyvwzrxl.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gt2nvbjuxrq.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gt2sejrqxdm.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gt2albgpaxr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gt2czejoqoy.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gt2nhqpuevv.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlunmarh.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gt2argkrcse.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gt2lmahrfjl.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gt2pwosrobm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gt2offhcgjo.html

[S08] C：动态内存分配与释放
来源：http://dali.c1oappe.top/Article/details/gt2shluxegs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gt2eiuqlmpj.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gt2xkcydolc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2awqyoobw.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gt2oclswabi.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gt2nmnwajak.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2lbhujnig.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gt2xeokmxmf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2rxwngwvf.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2jxrostyx.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wntrigpw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gt2jbhzakdr.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gt2ugwvxhwh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gt2upggtmyf.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2ilduqnxr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gt2ppgrnakx.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwqkcpzc.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gt2nzvmqouc.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gt2bajnnhoa.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gt2uffgpafn.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2nlceztts.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gt2fgfuydie.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2deiinbew.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gt2xtoravon.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gt2gvadkwsj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnwjjtjm.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gt2emcygkxf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2ryedlgyi.html

[S21] C：字符类别判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2diwfzpws.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gt2gicmcyhi.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epcxwtkp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gt2ifjlteqn.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gt2notzgyit.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gt2vrhxepij.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gt2aqkcevff.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gt2nxjdtcbd.html

[S25] C：内存拷贝
来源：http://dali.xylfe.cn/Article/details/gt2ymhpvfhq.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uckivism.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gt2pcrcibdg.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gt2aibdunlp.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gt2kfhdgyfz.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2tewlwzbz.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gt2cfiygnfc.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gt2tcqthvio.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gt2kjcowock.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gt2cijmwumf.html

[S30] C：头文件保护
来源：http://dali.nwbrower.top/Article/details/gt2rczhuwat.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gt2euqvyjmn.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gt2ryxunkka.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gt2iplwrokg.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2ylyjeniz.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gt2yjbgnpne.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ibmqrufe.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gt2lnjmfvtv.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gt2pfgztgkv.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gt2byslbkps.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzoeaebr.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2gxatzoho.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gt2aupzjtlg.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbkdyjsk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2qfdpwmhx.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gt2gwzuikiz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2rldiorhw.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gt2kfzaxhit.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xylfe.cn/Article/details/gt2lbciaxpf.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gt2cmcctmsj.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2csxtyuae.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gt2ivmibwyl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gt2pfiatrgb.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gt2xwovvkso.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gt2gssskbfu.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2rwulebui.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anhrgceg.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gt2crgyqvwl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gt2gpkusndb.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gt2vbmhtyor.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2uxnvfpqo.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gt2uhwuwmma.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gt2cugymalk.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gt2uozndxbx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gt2cozmexem.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gt2ckzsptww.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gt2ytoimwkg.html


<!-- 参考信息 -->